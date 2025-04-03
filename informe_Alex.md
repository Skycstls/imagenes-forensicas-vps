# Informe de extraccion

## Información General

- Fecha y hora de la extraccion: 2025-04-03 12:34:40
- Responsable de la extracción: Alejandro Rodriguez
- Motivo de la extracción: Relevancia en un caso de asesinato ·el balatro"

## Descripción del VPS

- IP pública: 172.233.121.53
- IP privada:
- Sistema Operativo y version: PRETTY_NAME="Ubuntu 24.04.2 LTS"
NAME="Ubuntu"
VERSION_ID="24.04"
VERSION="24.04.2 LTS (Noble Numbat)"
VERSION_CODENAME=noble
ID=ubuntu
ID_LIKE=debian
HOME_URL="https://www.ubuntu.com/"
SUPPORT_URL="https://help.ubuntu.com/"
BUG_REPORT_URL="https://bugs.launchpad.net/ubuntu/"
PRIVACY_POLICY_URL="https://www.ubuntu.com/legal/terms-and-policies/privacy-policy"
UBUNTU_CODENAME=noble
LOGO=ubuntu-logo
Linux localhost 6.8.0-53-generic #55-Ubuntu SMP PREEMPT_DYNAMIC Fri Jan 17 15:37:52 UTC 2025 x86_64 x86_64 x86_64 GNU/Linux
- Recursos asignados: Architecture:             x86_64
  CPU op-mode(s):         32-bit, 64-bit
  Address sizes:          48 bits physical, 48 bits virtual
  Byte Order:             Little Endian
CPU(s):                   1
  On-line CPU(s) list:    0
Vendor ID:                AuthenticAMD
  BIOS Vendor ID:         QEMU
  Model name:             AMD EPYC 7713 64-Core Processor
    BIOS Model name:      pc-q35-7.2  CPU @ 2.0GHz
    BIOS CPU family:      1
    CPU family:           25
    Model:                1
    Thread(s) per core:   1
    Core(s) per socket:   1
    Socket(s):            1
    Stepping:             1
    BogoMIPS:             4000.00
    Flags:                fpu vme de pse tsc msr pae mce cx8 apic sep mtrr pge mca cmov pat pse36 clflush mmx fxsr sse sse2 syscall 
                          nx mmxext fxsr_opt pdpe1gb rdtscp lm rep_good nopl cpuid extd_apicid tsc_known_freq pni pclmulqdq ssse3 fm
                          a cx16 pcid sse4_1 sse4_2 x2apic movbe popcnt tsc_deadline_timer aes xsave avx f16c rdrand hypervisor lahf
                          _lm cmp_legacy cr8_legacy abm sse4a misalignsse 3dnowprefetch osvw perfctr_core ssbd ibrs ibpb stibp vmmca
                          ll fsgsbase tsc_adjust bmi1 avx2 smep bmi2 erms rdseed adx smap clflushopt clwb sha_ni xsaveopt xsavec xge
                          tbv1 xsaves clzero xsaveerptr wbnoinvd arat umip pku ospke vaes vpclmulqdq rdpid fsrm arch_capabilities
Virtualization features:  
  Hypervisor vendor:      KVM
  Virtualization type:    full
Caches (sum of all):      
  L1d:                    64 KiB (1 instance)
  L1i:                    64 KiB (1 instance)
  L2:                     512 KiB (1 instance)
  L3:                     16 MiB (1 instance)
NUMA:                     
  NUMA node(s):           1
  NUMA node0 CPU(s):      0
Vulnerabilities:          
  Gather data sampling:   Not affected
  Itlb multihit:          Not affected
  L1tf:                   Not affected
  Mds:                    Not affected
  Meltdown:               Not affected
  Mmio stale data:        Not affected
  Reg file data sampling: Not affected
  Retbleed:               Not affected
  Spec rstack overflow:   Vulnerable: Safe RET, no microcode
  Spec store bypass:      Mitigation; Speculative Store Bypass disabled via prctl
  Spectre v1:             Mitigation; usercopy/swapgs barriers and __user pointer sanitization
  Spectre v2:             Mitigation; Retpolines; IBPB conditional; IBRS_FW; STIBP disabled; RSB filling; PBRSB-eIBRS Not affected; 
                          BHI Not affected
  Srbds:                  Not affected
  Tsx async abort:        Not affected
               total        used        free      shared  buff/cache   available
Mem:           961Mi       270Mi       249Mi       944Ki       594Mi       691Mi

- Aplicaciones o servicios en ejecucion:
 -Servicios:  UNIT                        LOAD   ACTIVE SUB     DESCRIPTION                                   
  cron.service                loaded active running Regular background program processing daemon
  dbus.service                loaded active running D-Bus System Message Bus
  getty@tty1.service          loaded active running Getty on tty1
  haveged.service             loaded active running Entropy Daemon based on the HAVEGE algorithm
  polkit.service              loaded active running Authorization Manager
  rsyslog.service             loaded active running System Logging Service
  serial-getty@ttyS0.service  loaded active running Serial Getty on ttyS0
  ssh.service                 loaded active running OpenBSD Secure Shell server
  systemd-journald.service    loaded active running Journal Service
  systemd-logind.service      loaded active running User Login Management
  systemd-networkd.service    loaded active running Network Configuration
  systemd-resolved.service    loaded active running Network Name Resolution
  systemd-timesyncd.service   loaded active running Network Time Synchronization
  systemd-udevd.service       loaded active running Rule-based Manager for Device Events and Files
  udisks2.service             loaded active running Disk Manager
  unattended-upgrades.service loaded active running Unattended Upgrades Shutdown
  upower.service              loaded active running Daemon for power management
  user@0.service              loaded active running User Manager for UID 0

Legend: LOAD   → Reflects whether the unit definition was properly loaded.
        ACTIVE → The high-level unit activation state, i.e. generalization of SUB.
        SUB    → The low-level unit activation state, values depend on unit type.

18 loaded units listed.
- Aplicaciones: 
USER         PID %CPU %MEM    VSZ   RSS TTY      STAT START   TIME COMMAND
root         736  0.0  2.3 109676 22912 ?        Ssl  13:55   0:00 /usr/bin/python3 /usr/share/unattended-upgrades/unattended-upgrad
root           1  0.0  1.3  22404 13456 ?        Ss   13:55   0:01 /sbin/init
root        1389  0.0  1.3 468820 13312 ?        Ssl  14:19   0:00 /usr/libexec/udisks2/udisksd
root         294  0.0  1.3  33964 12936 ?        S<s  13:55   0:00 /usr/lib/systemd/systemd-journald
systemd+     423  0.0  1.2  19732 12672 ?        Ss   13:55   0:00 /usr/lib/systemd/systemd-resolved
root         851  0.0  1.1  20044 11008 ?        Ss   13:59   0:00 /usr/lib/systemd/systemd --user
systemd+     634  0.0  0.9  19004  9344 ?        Ss   13:55   0:00 /usr/lib/systemd/systemd-networkd
root         844  0.0  0.9  15540  9200 ?        Ss   13:59   0:00 sshd: root@pts/0
root         678  0.0  0.8  17976  8704 ?        Ss   13:55   0:00 /usr/lib/systemd/systemd-logind
root        1371  0.0  0.8 313760  8704 ?        Ssl  14:19   0:00 /usr/libexec/upowerd
polkitd     1377  0.0  0.8 308160  7936 ?        Ssl  14:19   0:00 /usr/lib/polkit-1/polkitd --no-debug
systemd+     424  0.0  0.7  91020  7808 ?        Ssl  13:55   0:00 /usr/lib/systemd/systemd-timesyncd
root         830  0.0  0.7  12020  7808 ?        Ss   13:55   0:00 sshd: /usr/sbin/sshd -D [listener] 0 of 10-100 startups
root         389  0.0  0.7  29060  7656 ?        Ss   13:55   0:00 /usr/lib/systemd/systemd-udevd
root         942  0.0  0.6  10000  6272 pts/0    Ss   13:59   0:00 -bash
syslog       707  0.0  0.5 222508  5888 ?        Ssl  13:55   0:00 /usr/sbin/rsyslogd -n -iNONE
message+     669  0.0  0.5   9804  5248 ?        Ss   13:55   0:00 @dbus-daemon --system --address=systemd: --nofork --nopidfile --s
root         626  0.0  0.5   8632  4984 ?        Ss   13:55   0:00 /usr/sbin/haveged --Foreground --verbose=1
root        3967  0.0  0.4  10884  4480 pts/0    R+   14:51   0:00 ps aux --sort=-%mem
root         852  0.0  0.3  21148  3372 ?        S    13:59   0:00 (sd-pam)
root         668  0.0  0.2   6824  2688 ?        Ss   13:55   0:00 /usr/sbin/cron -f -P
root         732  0.0  0.2   5720  2176 ttyS0    Ss+  13:55   0:00 /sbin/agetty -o -p -- \u --keep-baud 115200,57600,38400,9600 - vt
root         759  0.0  0.1   6104  1920 tty1     Ss+  13:55   0:00 /sbin/agetty -o -p -- \u --noclear - linux
root           2  0.0  0.0      0     0 ?        S    13:55   0:00 [kthreadd]
root           3  0.0  0.0      0     0 ?        S    13:55   0:00 [pool_workqueue_release]
root           4  0.0  0.0      0     0 ?        I<   13:55   0:00 [kworker/R-rcu_g]
root           5  0.0  0.0      0     0 ?        I<   13:55   0:00 [kworker/R-rcu_p]
root           6  0.0  0.0      0     0 ?        I<   13:55   0:00 [kworker/R-slub_]
root           7  0.0  0.0      0     0 ?        I<   13:55   0:00 [kworker/R-netns]
root           8  0.0  0.0      0     0 ?        I    13:55   0:00 [kworker/0:0-cgroup_destroy]
root           9  0.0  0.0      0     0 ?        I<   13:55   0:00 [kworker/0:0H-kblockd]
root          10  0.0  0.0      0     0 ?        I    13:55   0:01 [kworker/0:1-events]
root          12  0.0  0.0      0     0 ?        I<   13:55   0:00 [kworker/R-mm_pe]
root          13  0.0  0.0      0     0 ?        I    13:55   0:00 [rcu_tasks_kthread]
root          14  0.0  0.0      0     0 ?        I    13:55   0:00 [rcu_tasks_rude_kthread]
root          15  0.0  0.0      0     0 ?        I    13:55   0:00 [rcu_tasks_trace_kthread]
root          16  0.0  0.0      0     0 ?        S    13:55   0:00 [ksoftirqd/0]
root          17  0.0  0.0      0     0 ?        I    13:55   0:00 [rcu_preempt]
root          18  0.0  0.0      0     0 ?        S    13:55   0:00 [migration/0]
root          19  0.0  0.0      0     0 ?        S    13:55   0:00 [idle_inject/0]
root          20  0.0  0.0      0     0 ?        S    13:55   0:00 [cpuhp/0]
root          21  0.0  0.0      0     0 ?        S    13:55   0:00 [kdevtmpfs]
root          22  0.0  0.0      0     0 ?        I<   13:55   0:00 [kworker/R-inet_]
root          24  0.0  0.0      0     0 ?        S    13:55   0:00 [kauditd]
root          25  0.0  0.0      0     0 ?        S    13:55   0:00 [khungtaskd]
root          26  0.0  0.0      0     0 ?        S    13:55   0:00 [oom_reaper]
root          28  0.0  0.0      0     0 ?        I<   13:55   0:00 [kworker/R-write]
root          29  0.0  0.0      0     0 ?        S    13:55   0:00 [kcompactd0]
root          30  0.0  0.0      0     0 ?        SN   13:55   0:00 [ksmd]
root          31  0.0  0.0      0     0 ?        SN   13:55   0:00 [khugepaged]
root          32  0.0  0.0      0     0 ?        I<   13:55   0:00 [kworker/R-kinte]
root          33  0.0  0.0      0     0 ?        I<   13:55   0:00 [kworker/R-kbloc]
root          34  0.0  0.0      0     0 ?        I<   13:55   0:00 [kworker/R-blkcg]
root          35  0.0  0.0      0     0 ?        S    13:55   0:00 [irq/9-acpi]
root          36  0.0  0.0      0     0 ?        I<   13:55   0:00 [kworker/R-tpm_d]
root          37  0.0  0.0      0     0 ?        I<   13:55   0:00 [kworker/R-ata_s]
root          38  0.0  0.0      0     0 ?        I<   13:55   0:00 [kworker/R-md]
root          39  0.0  0.0      0     0 ?        I<   13:55   0:00 [kworker/R-md_bi]
root          40  0.0  0.0      0     0 ?        I<   13:55   0:00 [kworker/R-edac-]
root          41  0.0  0.0      0     0 ?        I<   13:55   0:00 [kworker/R-devfr]
root          42  0.0  0.0      0     0 ?        S    13:55   0:00 [watchdogd]
root          43  0.0  0.0      0     0 ?        I<   13:55   0:00 [kworker/0:1H]
root          44  0.0  0.0      0     0 ?        S    13:55   0:00 [kswapd0]
root          45  0.0  0.0      0     0 ?        S    13:55   0:00 [ecryptfs-kthread]
root          46  0.0  0.0      0     0 ?        I<   13:55   0:00 [kworker/R-kthro]
root          47  0.0  0.0      0     0 ?        I<   13:55   0:00 [kworker/R-acpi_]
root          48  0.0  0.0      0     0 ?        S    13:55   0:00 [scsi_eh_0]
root          49  0.0  0.0      0     0 ?        I<   13:55   0:00 [kworker/R-scsi_]
root          50  0.0  0.0      0     0 ?        S    13:55   0:00 [scsi_eh_1]
root          51  0.0  0.0      0     0 ?        I<   13:55   0:00 [kworker/R-scsi_]
root          54  0.0  0.0      0     0 ?        I<   13:55   0:00 [kworker/R-mld]
root          55  0.0  0.0      0     0 ?        I<   13:55   0:00 [kworker/R-ipv6_]
root          62  0.0  0.0      0     0 ?        I<   13:55   0:00 [kworker/R-kstrp]
root          64  0.0  0.0      0     0 ?        I<   13:55   0:00 [kworker/u3:0]
root          69  0.0  0.0      0     0 ?        I<   13:55   0:00 [kworker/R-crypt]
root          79  0.0  0.0      0     0 ?        I<   13:55   0:00 [kworker/R-charg]
root         139  0.0  0.0      0     0 ?        S    13:55   0:00 [scsi_eh_2]
root         140  0.0  0.0      0     0 ?        I<   13:55   0:00 [kworker/R-scsi_]
root         141  0.0  0.0      0     0 ?        S    13:55   0:00 [scsi_eh_3]
root         142  0.0  0.0      0     0 ?        I<   13:55   0:00 [kworker/R-scsi_]
root         143  0.0  0.0      0     0 ?        S    13:55   0:00 [scsi_eh_4]
root         144  0.0  0.0      0     0 ?        I<   13:55   0:00 [kworker/R-scsi_]
root         145  0.0  0.0      0     0 ?        S    13:55   0:00 [scsi_eh_5]
root         146  0.0  0.0      0     0 ?        I<   13:55   0:00 [kworker/R-scsi_]
root         147  0.0  0.0      0     0 ?        S    13:55   0:00 [scsi_eh_6]
root         148  0.0  0.0      0     0 ?        I<   13:55   0:00 [kworker/R-scsi_]
root         149  0.0  0.0      0     0 ?        S    13:55   0:00 [scsi_eh_7]
root         150  0.0  0.0      0     0 ?        I<   13:55   0:00 [kworker/R-scsi_]
root         151  0.0  0.0      0     0 ?        I    13:55   0:00 [kworker/u2:5-events_unbound]
root         157  0.0  0.0      0     0 ?        I<   13:55   0:00 [kworker/R-ttm]
root         179  0.0  0.0      0     0 ?        I<   13:55   0:00 [kworker/R-raid5]
root         220  0.0  0.0      0     0 ?        S    13:55   0:00 [jbd2/sda-8]
root         221  0.0  0.0      0     0 ?        I<   13:55   0:00 [kworker/R-ext4-]
root         317  0.0  0.0      0     0 ?        I<   13:55   0:00 [kworker/R-kmpat]
root         318  0.0  0.0      0     0 ?        I<   13:55   0:00 [kworker/R-kmpat]
root         429  0.0  0.0      0     0 ?        S    13:55   0:00 [psimon]
root         637  0.0  0.0      0     0 ?        I<   13:55   0:00 [kworker/R-cfg80]
root         857  0.0  0.0      0     0 ?        S    13:59   0:00 [psimon]
root         984  0.0  0.0      0     0 ?        I<   13:59   0:00 [kworker/R-tls-s]
root        1441  0.0  0.0      0     0 ?        I    14:20   0:00 [kworker/u2:3-events_power_efficient]
root        3155  0.0  0.0      0     0 ?        S    14:27   0:00 [psimon]
root        3611  0.0  0.0      0     0 ?        I    14:29   0:00 [kworker/u2:1-events_unbound]
root        3748  0.0  0.0      0     0 ?        I    14:37   0:00 [kworker/u2:0-events_power_efficient]
root        3933  0.0  0.0      0     0 ?        I    14:49   0:00 [kworker/u2:2-events_unbound]
root        3946  0.0  0.0      0     0 ?        I    14:50   0:00 [kworker/0:2]

## Metodología

- Herramientas utilizadas: dd y gzip
- Comandos y parametros usados:

## Integridad de la imagen

- Hash de la extracción:
61e4144f52e622a134524c6d9e18c20271b5cdc9afb5e60531ad36aca8154a42

## Firma de la imagen

- Algoritmo de hash usado: sha256
- Metodo de firma digital: Generacion de claves RSA
- Clave publica del firmante
- Comandos usados para la firma :
```
openssl genpkey -algorithm RSA -out privada.pem -pkeyopt rsa_keygen_bits:4096
```
```
openssl rsa -pubout -in privada.pem -out publica.pem
```
```
openssl dgst -sha256 -sign privada.pem -out firma.bin balatro_backup.img.gz
```
```
openssl dgst -sha256 -verify publica.pem -signature firma.bin balatro_backup.img.gz
```
- Ubicacion de los archivos de firma y hash : https://limewire.com/d/PcQpd#VN2EsPAIhC
