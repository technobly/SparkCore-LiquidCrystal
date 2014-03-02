SparkCore-LiquidCrystal
=======================

An Implementation of Arduino's LiquidCrystal library for the Spark Core

Universally Supports:
* Standard Hitachi HD44780 based LCDs in 4-bit mode
* Adafruit's 16x2 OLED Display (Winstar)
* Sparkfun's 16x2 OLED Display (ADH Technology Co. Ltd.)

Grab the RAW version of each file and place into your web IDE as follows:

![image](http://i.imgur.com/ovx14kb.png)

If you are building locally, place the files here:

```
..\core-firmware\inc\LiquidCrystal.h
..\core-firmware\src\application.cpp (renamed from Spark-HelloSparky.cpp)
..\core-firmware\src\LiquidCrystal.cpp
..\core-firmware\src\build.mk (optional, if you have your own make file going, just add the LiquidCrystal.cpp to it)
```