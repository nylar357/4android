# 4android
Some tweaks - Google Pixel 3a Sargo
## BlackenedMOD
https://forum.xda-developers.com/pixel-3-xl/development/mod-blackenedmod-v1-0-pixel-3-pixel-3-xl-t3887158
For Blackenmods you'll just need to drop the script into /data/adb/service.d.

## KTWEAK

https://forum.xda-developers.com/android/software/module-ktweak-evidence-t4148447
For Ktweaks theres some debate on this and currently the APK & Magisk Module on the XDA Page don't install 
on Android 11 (which is what I'm using) But fortunately I've found a workaround that successfully installs the 
module and keeps the script up to date on boot.

First Step : which I've done for you already is to change the script to #!/system/bin/sh then adjust the max
cpu freq.  

Second Step : Is to flash the script with whatever kernel manager you prefer I use SP Kernel Auditor, and 
check it as run on boot.  Then move the script out of your downloads folder into your standard home directory.
Then copy it to /data/adb/service.d and change permissions to 0755.  Reboot and you'll notice the Log now updating to 
tell you its running correctly and if you check magisk KTweak Module now appears correctly in your module tab.


![preview](Screenshot_20201022-051829.png)

![preview](Screenshot_20201022-051929.png)
