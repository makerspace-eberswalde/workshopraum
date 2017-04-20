# workshopraum

## Links
* mutliboot: http://askubuntu.com/questions/427053/pxeboot-multiple-image
* preseed file: http://www.gtkdb.de/index_34_2515.html
* Appendix B. Automating the installation using preseeding https://help.ubuntu.com/lts/installation-guide/i386/apb.html
* preseed example file: https://www.debian.org/releases/wheezy/example-preseed.txt
* netboot: https://help.ubuntu.com/community/Installation/Netboot
* pxe-boot: https://wiki.ubuntuusers.de/PXE-Boot/
* multi image instructions: https://www.howtoforge.com/ubuntu_pxe_install_server_p3
* best guide: https://help.ubuntu.com/community/PXEInstallMultiDistro

## folders
* tftp: /var/lib/tftpboot
* dnsmasq: /etc/dnsmasq.conf
* syslinux: /usr/lib/syslinux (copy pxelinux.0 and vesainfo.c32 from here to /var/lib/tftpboot)

## TODO
* ask Frank how he installed automatic run level for dnsmasq
