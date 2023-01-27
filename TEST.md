Osso cape for BeagleBone black preinstalled Debian GNU/Linux for tests.

WARNING: this will install a debian system in the internal eMMC, backup any data before to proceeding!!!

Copy the disk image on a microSD card of 4 or more gigabytes with:

* wget https://web.archive.org/web/20230127104226/http://www.nexlab.net/Ossotest.img.xz
* xzcat Ossotest.img.xz | dd of=/dev/sdX

where /dev/sdX is the device of your microSD card.

Insert the microSD in the beaglebone black slot and start the board pressing the microswitch closest to the microSD.

Take a coffee break, it will need some times to flash your eMMC. When done, the 4 blue user leds will fixed light on.

Switch off the BeagleBone, remove the microSD, start the BeagleBone again.

The Osso test install get an IP address by DHCP and have a second static IP at 192.168.181.1, the root password is osso

Enjoy!
