Update
======

Android Application Update
--------------------------

Firmware Update
---------------

To update the firmware from USB you have to short the pin 1 CN4 with pin 2 CN4.

.. image:: _images/louvre_boot_jumpers.jpg

Then plug the mini-usb from the PC to the board.

.. image:: _images/louvre_usb.jpg

The LPC11U will run in boot mode and your PC will plug the board as a mass storage device. To update all you need is copy the new firmware renamed "firmware.bin" in the mass storage. Delete first the old one before to copy one newer.
 

