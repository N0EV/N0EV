```bash
kali@fsociety:~$ whoami
n0ev

kali@fsociety:~$ grep n0ev /etc/passwd
n0ev:x:1000:1000:Noé Valladolid:/home/n0ev:/bin/bash

kali@fsociety:~$ uname -a
Linux kali 6.6.0-kali1-amd64 #1 SMP PREEMPT_DYNAMIC Debian 6.6.0-kali1-1kali1 x86_64 GNU/Linux

kali@fsociety:~$ id
uid=1000(n0ev) gid=1000(n0ev) groups=1000(n0ev),4(adm),24(cdrom),27(sudo),30(dip),46(plugdev),120(lpadmin),131(lxd),132(sambashare)

kali@fsociety:~$ cat ~/.profile
Técnico en SMR
Estudiante de ASIR

kali@fsociety:~$ ls -la ~/.skills
-rw-r--r-- 1 n0ev n0ev 512 Dec 28 19:50 .skills

kali@fsociety:~$ cat ~/.skills
> OS: Debian, Ubuntu Server, Windows Server
> Networks: Wireshark, Cisco Packet Tracer, SSH/Putty
> Virtualization: VirtualBox
> Tools: Bash, Git, VS Code

kali@fsociety:~$ curl -s https://ko-fi.com/noe_vallad
[+] Support this research: https://ko-fi.com/noe_vallad

kali@fsociety:~$ exit
logout
Connection closed.
```
