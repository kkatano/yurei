# Yurei
A Tenkeyless PCB inspired by Phantom, designed for customizing Filco Majestouch 2

## Features
 * QMK Firmware
 * Teensy 2.0 controller
 * Minimal layout support
 * No LEDs and no underglow
 * All switches are south facing
 * Compatible with Filco Majestouch 2 case
 * Designed with KiCAD 5.1.4

## Supported Layouts
 * ANSI

 [![keyboard-layout](images/keyboard-layout.png)

## Supported Switches
 * Cherry MX and Cherry MX style switches

## Supported Cases
 * Filco Majestouch 2

### Note
 * A bit modification to Filco case is required to install the USB cable.
 * Some other keyboard cases may also be compatible, but they have not been tested.
 * YMDK aluminum case is not compatible (almost good but plate and pcb are slightly too thick, so that it causes a gap between the top and bottom cases).

## BOM

TBA

## Firmware

TBA

## Lisence

Yurei is provided under the MIT License.

## Credits

### [The Phantom](http://bathroomepiphanies.com/keyboards/phantom/)

Source of inspiration.

### Teensy library for KiCAD

Teensy symbol and footprint are based on XenGi's libraries released under the MIT license.

#### [teensy_library](https://github.com/XenGi/teensy_library)

Copyright (c) 2015 Ricardo Band  
https://github.com/XenGi/teensy_library/blob/master/LICENSE 

#### [teensy.pretty](https://github.com/XenGi/teensy.pretty)

Copyright (c) 2015 Ricardo Band  
https://github.com/XenGi/teensy.pretty/blob/master/LICENSE

### [KiCad Libraries](https://kicad-pcb.org/libraries/)

All symbols and footprints except Teensy are based on The KiCad libraries.

### [Keyboard Layouter Plugin](https://github.com/yskoht/keyboard-layouter)

Handy plugin to place the switches.

### [keyboard-layout-editor.com](http://www.keyboard-layout-editor.com/)

Used to generate keyboard layout data to be input to Keyboard Layouter.