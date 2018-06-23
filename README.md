# ConfigMarlin118forAnycubicDeltaPlus

This an "unofficial but working" Marlin 1.1.8 configuration for Anycubic Delta Plus

These header files have been created to adapt Marlin 1.1.8 to the Anycubic Delta Plus printer.

There are other firmwares (official and unofficial) but given the problems they have I decided to create a configuration that allows to use the latest (at least for the moment) version of Marlin with this formidable printer.

This version of Marlin has important improvements compared to the previous ones. For example: acceleration, leveling that really works with kossel, etc.

**How it works**

You only need to copy these two files overwriting the ones in the marlin folder of the official distribution, which you can find here:

https://github.com/MarlinFirmware/Marlin

https://github.com/MarlinFirmware/Marlin/releases/tag/1.1.8

Then you must compile and upload to the Trigorilla board of your printer, following the instructions that you will find here:

http://marlinfw.org/docs/basics/install.html

**Compiled version**

If you are lazy about compiling and uploading with the Arduino IDE, you can use the compiled version and upload it with Cura or any other software that allows you to upload a HEX.

**Config for Slic3r**

The "slic3r" folder contains the configuration used for testing with Slic3r.


