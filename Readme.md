/* ------------
Library only works for Arduino Uno and others based on the ATmega328.
The pins are hard coded into the library for better performance, only port D and the SPI Pins are used.

HUB08-Pin | Arduino Pin | Note
  LA / A  |     4       | Line select A
  LB / B  |     5       | Line select B 
  LC / C  |     6       | Line select C
  LD / D  |     7       | Line select D
  CLK     |   13 (SCK)  | Serial clock
  R1 / R  |   11 (MOSI) | Serial Data (Red pixels)
  OE / EN |     3       | Output Enable (PWM brightness control)
 LAT / STB|     2       | Latch
  
The library increases the Timer2 frequency so that the PWM runs on 32 kHz.
Affected are only the pins 3 and 11, both occupied by the interface.

-------------*/
