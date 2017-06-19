The Youtube Video : https://youtu.be/Qz51UelzByA

--+Notes : 

## The commands : 

1- dmesg | grep -i scsi =>> to get the drive = sdd [DRIVE]

2- ./cookpw.py THEPASSWORD >password.bin =>> THEPASSWORD = your passcode


3- Install 'sg3_utils' package for your distro depends on the distro you use ! 

4- sudo sg_raw -s 40 -i password.bin /dev/sdd c1 e1 00 00 00 00 00 00 28 00


## The Tools : 

* [WD-Decrypte](https://github.com/SifoHamlaoui/WD-Decrypte)
