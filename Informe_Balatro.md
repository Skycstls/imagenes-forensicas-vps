# Informe de extraccion

## Información General

- Fecha y hora de la extracción
    - Viernes, 4 de Abril de 2025 16:16
- Responsable de la extracción
    - Horacio David Capilla Martín
- Motivo de la extracción
    - Sospecha de incitar a la ludopatía

## Metodología

- Herramientas utilizadas
    - Autopsy
- Comandos y parametros usados
    - Partición
    - Ext4
    - UTF16

## Integridad de la imagen

- Hash de la extracción
    - **61e4144f52e622a134524c6d9e18c20271b5cdc9afb5e60531ad36aca8154a42**


## Usuarios reconocidos

- root
- balatro
- dev
- invitado

## Investigación de root

Durante la investigación en autopsy, entré primero a root, descubriendo varias carpetas

- .bashrc
- .cache/
- .config/
- .lesshst
- .profile
- .ssh/

### bashrc

Archivo de configuración de bash básico, nada importante.

### cache

Archiva llamado "motd.legal-displayed" al que no tenemos acceso, una investigación en internet revela que es un indicador utilizado por el sistema para saber si ya se ha mostrado el mensaje legal del MOTD (Message of the Day) al usuario.

### config/

Carpeta que contiene a su vez otras carpetas, "htop" y "neofetch".

Htop esta vacía y neofecth contiene un archivo de configuración para un programa con su mismo nombre.

### lesshst

Archivo de texto sin importancia

### profile

No se encontró mucho de utilidad

### ssh
.ssh con una clave que indicaba a la verdadera persona que se esconde tras Balatro, un tal roloccio.

## Investigación de Balatro
Comencé la investigación por el perfil de Balatro descubriendo varias carpetas:

-   .bash_history (intento de borrado)
-   .bash_logout (intento de borrado)
-   .bashrc (intento de borrado)
-   .config/
-   .profile (intento de borrado)
-   .wget-hsts (intento de borrado)
-   pruebas/
-   trabajo/

### bash_history
En este archivo que trató de ser eliminado podemos ver el historial de la terminal como todos los comandos lanzados, directorios creados, etc. No sabemos si está todo el historial guardado, pero si hay bastante.

Desde este sitio podemos localizar que tiene una flag oculta dentro de .config a la vez que un secreto dentro de esta misma carpeta.

Además, podemos registrar como estuvo tratando de descargar imagenes a la carpeta pruebas y como después copió estas imagenes a la de trabajo, donde borró 4 imagenes y un video en formato .mp4.

### bash_logout

Se trata de un script que limpia la pantalla una vez el usuario se desconecta.

### bashrc

Archivo de configuración de bash básico, nada importante.

### config/

Es una carpeta que contiene, a su vez, otras dos carpetas.

- oculto/
    - flag.txt
- secreto/
    - secret

flag.txt es un archivo de texto plano que dice:

```bash
Esta es la flag
```

Por su parte, secret es un archivo de texto plano también que contiene:

```bash
Este es un secreto
```

### profile

No se encontró mucho de utilidad

### wget-hsts

Archivo que guarda los hosts desde los que se trató de descargar algo usando el wget, contiene dominios como "reddit" , "imgur.com", "staticg.sportskeeda.com", "pbs.twimg.com", "content.nationalgeographic.com.es" y "cdnb.artstation.com"

### pruebas/

5 Imagenes que intentaron ser eliminados, en su mayoría memes y anime a excepción del logo de "X.com" y una imagen de una persona de color.

### trabajo/

Contiene varias imagenes que trataron de ser borradas, algunas son de la misma carpeta anterior (pruebas), además de un archivo .mp4 que también trató de ser eliminado.

## Investigación de logs

Tras investigar los archivos de los usuarios, hay cierta actividad en el usuario de root que indica el posible uso y, por lo tanto instalación, de varios programas.

Para investigar esto, veremos los logs de apt dentro de la carpeta "var" desde el origen de la imagen.

Una vez nos posicionamos en "/var/log/apt" podemos ver archivos como "eiopp.log.xz", "history.log" y "term.log"

### eiopp.log.xz

Archivo encriptado sin mucho que ver.

### history.log

Log en texto plano que contiene la linea que más nos interesaba, la de instalación de varios programas:

```bash
apt install -y htop nano vim curl wget git python3 net-tools tree neofetch
```

### term.log

Registro de instalaciones de varios programas