
.. _quick:

Quick start guide
=================

.. warning::

	The demo have been tested with nexus tablet, in this guide we will refer to it.

Unboxing
--------

The product is supplied with the box like this:

.. image:: _images/box_closed.jpg

And this is the content of box:

.. image:: _images/box_opened.jpg

The board itself has been programmed with the demo.

Install Android Application
---------------------------

.. warning::

 This application works on tablet and smartphone with android system. Not all device provided by antenna NFC are suited: if the antenna is too small cannot supply enough energy required to the Louvre board to run the demo.
 However the most device in the market are capable to work with the board without problems.
 
| Now let's to see how install the application. An Android application is stored in an APK file, you must install the APK on you Android device in order to run it.
| The easiest way is to download the file from `ArchiTech website <http://www.architechboards.org/>`_ directly by your device.
| Before to start, you have to enable installing from **Unknown Sources**. To do this follow next steps:
|

1. open the **Application** menu and click on the **Settings** application.

2. Select **Applications** from the **Settings** menu then select **Security**

3. Check the first selection, **Unknown Sources** so you can install an APK file from a location other than the Android Market. A warning message will be desplayed, select **OK** to continue.

| Now, before to download and install the application, search for a free file manager, such as **File Manager (Explorer)** by Cheetah Mobile, and install it from the market.
| Once installed, dowload the APK file with the browser of the Android device then open **File Manager**. The program will provide a list of the SD card contents, then execute APK file clicking on APK filename.
| A new screen showing the selected application's name at the top is displayed. To install the application, just click on the **Install** button on the bottom of the screen.
| Finally, a new screen is displayed once the installation is complete and you can choose to run the application by clicking **Open** button.
|
| After installed the application we are ready to test the Louvre board with the two following demos:

Demo without Mini-USB cable
---------------------------

This demo has the purpose to show how the Louvre can run getting energy only from the NFC and the communication from the android device to the Louvre board.

1. Start the application on the android device:

.. image:: _images/nfcget_icon.jpg

2. The application displays the images that you can sent to the Louvre. Select an image do you like:

.. image:: _images/nfcget_ui.png

3. Lay down the tablet on the Louvre. The Android device must cover all the antenna area of the Louvre.

.. image:: _images/louvre_tablet.jpg

4. Once the data transfer is done a message is reported on the tablet. Do not remove the device from the Louvre until the e-ink display doesn't show the selected image.

.. image:: _images/nfcget_written.png

5. Finally the display will show the image selected

.. image:: _images/nfcget_success.jpg


Demo with Mini-USB cable
------------------------

This demo has the purpose to show the communication from the Louvre board to the android device.

1. Check the jumper **CN4** is setted correctly:

.. image:: _images/louvre_run_jumpers.jpg

2. Insert mini-usb cable from PC to the CNX connector of the board.

.. image:: _images/louvre_usb.jpg

3. The Louvre display on the e-ink screen the temperature read from **SEN300** sensor and the last capacitive button pressed.

.. image:: _images/louvre_usb_none.jpg

4. If you press a capacitive button S1, S2, S3 or S4 this will displayed on the screen.

.. image:: _images/louvre_usb_s2.jpg
