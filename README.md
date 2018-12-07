<!-- -*- mode: markdown; fill-column: 8192 -*- -->

Splitography sketch
===================

[![CI status](https://ci.madhouse-project.org/api/badges/algernon/Splitography-Sketch/status.svg?branch=master)](https://ci.madhouse-project.org/algernon/Splitography-Sketch)

This is a complete, usable Sketch for the [SOFT/HRUF Splitography][splitography], that models the [default layout][splitography:default-layout].

 [splitography]: https://softhruf.love/collections/writers
 [splitography:default-layout]: https://github.com/sdothum/qmk_firmware/blob/d865c82efa19beb7cb593e7d3affb2311017833e/keyboards/splitography/keymaps/default/

<a id="building"></a>
# Building & flashing

To build the firmware, one needs to have [Arduino][arduino] installed, along with `make` and `git`, and a UNIX-like environment. It is possible to build and flash from Windows too, but at the time of this writing, only the UNIX command-line tooling has been tested.

 [arduino]: https://www.arduino.cc/

To build, just clone the repository, and run `make`, and it will bootstrap itself (sans Arduino), and do the build. To flash, type `make flash`. You'll need [dfu-programmer][dfu-programmer] to upload new firmware.

 [dfu-programmer]: https://dfu-programmer.github.io/

When prompted to press `Enter`, put the board into bootloader mode, by pressing the reset button on the left side, beside the USB port.

<a id="license"></a>
# License

The code is released under the terms of the GNU GPL, version 3 or later. See the
COPYING file for details.
