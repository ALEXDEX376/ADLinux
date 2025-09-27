# ADLinux
A custom Linux distribution with a Linux kernel, Busybox and GRUB

Contains only Linux 6.12.49-lts kernel and Busybox 1.37.0 

![linux-logo](https://github.com/user-attachments/assets/1089a523-5eb2-4c4f-825b-d35486214542)

<img width="787" height="548" alt="Screenshot_20250927_113537" src="https://github.com/user-attachments/assets/71a48c9b-2c60-4df0-9223-91e4a95a2002" />
<img width="771" height="504" alt="Screenshot_20250927_113517" src="https://github.com/user-attachments/assets/30071187-abd4-4d4b-93e0-da2fa3c1b212" />



Grub will be unable to load the os so run these commands - 
''
set root=cd

linux /bzImage

initrd /initramfs.cpio.gz 
''
Any help would be appreciated here - https://www.reddit.com/r/Operatingsystems/comments/1nrnowk/adlinux_created_it_in_school_holidays/

iso also available on sourceforge - https://sourceforge.net/projects/adlinux/

please teach me how to install a package manager on here

Made with love by an indian kid named Advik 
who took 3 days to learn how to do it
