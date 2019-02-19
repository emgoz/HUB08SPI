# Simple Driver Library for HUB08 Chips

## Description
Library only works for Arduino Uno and others based on the ATmega328.
The pins are hard coded into the library for better performance, only port D and the SPI Pins are used.

## Pinout
-  LAT / STB -> Digital Pin 2 (D2)
-  OE / EN -> Digital Pin 3 (D3)
-  LA / A -> Digital Pin 4 (D4)
-  LB / B -> Digital Pin 5 (D5)
-  LC / C -> Digital Pin 6 (D6)
-  LD / D -> Digital Pin 7 (D7)
-  CLK    -> Digital Pin 13
-  R1 / R -> Digital Pin 11

## Timer Speeds
The library increases the Timer2 frequency so that the PWM runs on 32 kHz to control the brightness.
Affected are only the pins 3 and 11, both occupied by the interface.
