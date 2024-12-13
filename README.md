# Linux Kernel Series

This series is used to study the linux kernel . I am using a Beagle Bone Black for learning. I hope this is useful to you.

## Component
This repo included:

- 01 build image beagle bone
- 02 linux operating system overview
- 03 blink led
  
![image](https://github.com/user-attachments/assets/600cdd96-79cd-4ef5-b3d2-665f28f17e7c)


shutdown beagle bone black command

  	sudo shutdown now

permit read write

  	sudo chmod 0777 /dev/m_cdev

copy

copy into current dir

  	cp -r /home/s2nmt/work/work_space/05-control-led .

copy from A to B

	cp -r /home/user/source_folder /home/user/new_folder_name

compile userspace command

  	/home/s2nmt/work/beagle_bone_black/gcc-linaro-6.5.0-2018.12-x86_64_arm-linux-gnueabihf/bin/arm-linux-gnueabihf-gcc -o userspace userspace.c

check sdcard

    lsblk 
	
Mount sdcard

    sudo mount /dev/sdb1 /media/rootfs/

Copy file
  
    sudo cp led.ko /media/rootfs/home/debian/
Sync
  
    sync

Umount

    sudo umount /media/rootfs
	
**Author** Minh Tuan

 **Date** 02 November, 2024
