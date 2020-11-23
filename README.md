# Spoof your device
* This modules enables widevine L1 support for Netflix and Google photos unlimited storage [High Quality], allowing it to spoof your device model and and manufacturer.
* Compatible with any Xiaomeme phone with L1 Certification by default [Only for Netflix]
* This module does not alter your system.
* XDA thread https://forum.xda-developers.com/poco-f1/how-to/widevine-l1-neflix-t4181651/post83787201#post83787201
* Proof https://photos.app.goo.gl/bh9jtGUi2tUPgmoU6

# How to use 

* Install the module using Magisk Manager (manually downloading a zip from releases)
* Clear Netflix App data 
  Enjoy!

# Fix In case of bootloop

* Boot into twrp 
* Advanced > terminal emulator
* pwd (current dir)
* cd /cache (press enter key)
* pwd
* touch .disable_magisk
* ls -al ( it will show whether it created . disable_magisk)
* exit
* Reboot to system

Or 

* Boot into recovery
* Open file manager
* Locate data/adb/modules/ delete specific module and reboot
