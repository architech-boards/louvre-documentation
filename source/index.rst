Welcome to Louvre Board's documentation!
========================================

:Version: 1.0.0C
:Copyright: (C)2014 Silica an Avnet company
:Date: 16 Sep 2014

.. image:: _images/louvre_board.jpg

.. image:: _images/silica.png

.. image:: _images/nxp.jpg

.. image:: _images/ntag.jpg

.. image:: _images/android.jpg

.. index:: index

Introduction
============

| **Silica Louvre board** is an useful product to evaluate the capabilities of **NFC** with **NXP** technology.
| The Louvre is a low power consumption board, the power supply is supplied exclusively from the NFC antenna of the android device.
| The firmware provided can display on an **e-ink** screen the images sent by an **android application**.
|
| In this documentation we show step by step the features of the firmware and how debug it.
|

.. note::

	If you want quickly see how the demos work go here :ref:`quick`!

| For board schematics and source code it is needed the registration from `ArchiTech website <http://www.architechboards.org/>`_.
| If you are interested to develop on this board don't forget to read the :ref:`development` section.
|

**General Description**

* Small form factor
* ISO7816 ID1 form factor (creditcard)
* NXP NTAG I2C
* NXP Cortex M0 LPC11U37 Microcontroller
* 2.7 e-ink display
* SEN300 temperature sensor
* Micro-USB connector
* Possibility to operate without battery
* Full size antenna to maximize energy harvesting
* Four capacitive buttons to enable user interaction

Contents:

.. toctree::
   :maxdepth: 3
   
   quick
   development
   update
   board
   appendix

