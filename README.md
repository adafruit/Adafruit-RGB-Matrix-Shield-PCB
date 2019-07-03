## Adafruit RGB Matrix Display Shield PCB

<a href="http://www.adafruit.com/products/2601"><img src="assets/image.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit RGB Matrix Shield. PCB format is EagleCAD schematic and board layout

For more details, check out the product page at
* https://www.adafruit.com/product/2601

### Description

Our RGB matricies are dazzling, with their hundreds or even thousands of individual RGB LEDs. Compared to NeoPixels, they've got great density, power usage and the price-per-LED can't be beat. But...(isn't there always a but?) You need to use our special library to control them and they require a bunch of wires to be plugged in. Tougher than a single-wire connection for sure.

If you've got an Arduino-compatible board, with an ATmega328p chip (like our Metro 328) or SAMD21 (like the Metro M0) or even SAMD51 (like our Metro M4) this shield will make usage a snap! A little light soldering to attach the headers, connector and terminal block and you're ready to rock. Plug it onto your microcontroller board, and you'll be able to attach any RGB matrix with ease. This shield just takes care of the wiring for you!

For 800mA or less power usage on the matrix you can even 'borrow' the 5V power from the Arduino's regulator. This isn't good for projects where you have a lot of LEDs on at once but for scrolling text and light LED usage it will make wiring even easier because you dont need a separate power adapter. Of course, if you need 1 Amp or more, just use the 2x8 connector for data and use a separate 5V 2A or 5V 4A wall adapter directly to the panel.

Note that this shield is just a wiring adapter, if you have a Metro 328 you can only use 16x32 or possibly 32x32 matrices before you run out of RAM. For big panels, use a Metro M0 or M4 - those will work best thanks to their enormous RAM.

**Please note our Arduino library only supports 32-pixel tall matrices, so don't try using a 64x64 matrix, it doesn't work!**

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. See license.txt for additional details.
