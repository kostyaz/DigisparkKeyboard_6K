# DigisparkKeyboard_6K
Digispark USB HID keyboard with support for 6 simultaneous keystrokes.

## About
This Digispark Arduino library is based on [DigisparkKeyboard](https://github.com/digistump/DigistumpArduino/tree/master/digistump-avr/libraries/DigisparkKeyboard) by Digistump with addition of support for maximum of 6 simultaneous keypresses (not including modifier keys).
Also, the included [V-USB](https://www.obdev.at/products/vusb/index.html) library has been updated to the (then) latest version.

In order to keep the code clean and allow for easy updates, none of the existing V-USB source files have been changed. Only the following few files have been added from the original DigisparkKeyboard, with minimal changes:
 * scancode-ascii-table.h
 * usbconfig.h
 * DigiKeyboard_6K.h
 
 ## Installation
 Copy the internal `DigisparkKeyboard_6K` directory to Arduino IDE's `libraries`.
 
