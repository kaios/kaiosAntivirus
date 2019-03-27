KaiOS Anti-Virus Stick 2019 x86
www.kaios.org
Released under GNU GENERAL PUBLIC LICENSE 2.0
2019 KaiOS

KaiOS Anti-Virus is not responsible for any damages or data loss
caused by using the KaiOS Anti-Virus USB stick. By using the KaiOS
Anti-Virus USB stick, the user accepts all responsibility.

Use at your own RISK!

Source code:
https://github.com/kaios

Small, customizable 32-bit Linux anti-virus live distrobution using ClamAV.

Features:

-32-bit Kernel and binaries
-Networking support
-OpenSSH client and server support
-udhcpc support (Busybox DHCP Client)

Requirements:
- Computer connected to the internet or network
- BIOS with USB boot support (Legacy for UEFI boards)

Instructions:

Insert the KaiOS Anti-Virus 2019 Stick into the USB port on your PC.
Reboot your PC and enter the BIOS and change the boot order so the
bootable live USB stick is the first to boot. Save and exit the BIOS.
Please contact your manufacture before accessing the BIOS.

Reboot and KaiOS Anti-Virus 2019 will do the following:

- Boot into KaiOS Linux
- Mount all hard drives
- Create a virus vault in C:/Virus_Vault for infected files
- Download the latest virus database
- Scan all hard drives for virus
- Automatically move all virus to C:/Virus_Vault
- Create a virus report in C:/Virus_Vault
- Power off PC

Login:
Terminal screen has no authentication. SSH login authentication:

username: root
password: kaios
