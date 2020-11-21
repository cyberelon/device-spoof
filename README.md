# Spoof your device
This modules enables widevine L1 support for Netflix, allowing it to spoof your device model.

Features Compatible with any android phone with FHD display. Systemless: this module does not alter your system.

# How to use 

* Install the module using Magisk Manager (manually downloading a zip from releases)
* Clear Netflix App data 
  Enjoy!

# Fix In case of bootllop

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
