---
title: Política de Privacidade
order: 3
type: overview
---
<ContentColumn>
Hello Mihir,


This is a test!

--- 
# Steps for RPi Cross compilation
Check the mountpoint using following command
 lsblk 
 

 mount /dev/mmcblk0p1 /mnt
 mount /dev/mmcblk0p2 /mnt/boot
 https://hjortsberg.org/notes/Installing-Debian-packages-in-ArchLinux-using-debtap.html
 install qemu qemu-user qemu-user-static
 
 sudo cp /usr/bin/qemu-arm-static /run/media/mihir/writable/usr/bin
 
 https://forums.raspberrypi.com/viewtopic.php?t=8478
 
 mount -o bind /dev /mnt/dev  
mount -o bind /proc /mnt/proc  
mount -o bind /sys /mnt/sys



sudo mount -o bind /dev /run/media/mihir/writable/dev
sudo mount -o bind /proc/ /run/media/mihir/writable/proc
sudo mount -o bind /sys /run/media/mihir/writable/sys
sudo mount -t devpts none /run/media/mihir/writable/dev/pts

 sudo chroot /run/media/mihir/writable /bin/bash
 
 (loggedin as root)
 source /opt/ros/galactic/setup.zsh
 
  colcon --log-level=debug build --packages-skip-build-finished --packages-skip ros1_bridge 


  </ContentColumn>
