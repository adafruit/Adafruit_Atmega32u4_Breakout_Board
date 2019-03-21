# ATmega32u4 USB dev board

<a href="https://learn.adafruit.com/atmega32u4-breakout"><img src="assets/board.jpg?raw=true" width="500px"></a>

## About the Atmega32u4 Breakout board+

We like the AVR 8-bit family and were excited to see Atmel upgrade the series with a USB core. Having USB built in allows the chip to act like any USB device. For example, we can program the chip to 'pretend' it's a USB joystick, or a keyboard, or a flash drive! Another nice bonus of having USB built in is that instead of having an FTDI chip or cable (like an Arduino), we can emulate the serial port directly in the chip. This costs some Flash space and RAM space but that's the trade-off.
The only bad news about this chip is that it is surface mount only (SMT), which means that it is not easy to solder the way the larger DIP chips are. For that reason, we made a breakout board. The board comes with some extras like a fuse, a 16mhz crystal, USB connector and a button to start the bootloader.
