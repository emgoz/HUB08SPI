Library only works for Arduino Uno and others based on the ATmega328.
The pins are hard coded into the library for better performance, only port D and the SPI Pins are used.


  LA / A -> Digital Pin 4
  
  LB / B -> Digital Pin 5
  
  LC / C -> Digital Pin 6
  
  LD / D -> Digital Pin 7
  
  CLK    -> Digital Pin 13
  
  R1 / R -> Digital Pin 11
  
  OE / EN -> Digital Pin 3
  
  LAT / STB -> Digital Pin 2
  
The library increases the Timer2 frequency so that the PWM runs on 32 kHz.
Affected are only the pins 3 and 11, both occupied by the interface.
