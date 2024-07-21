ZMK Firmware for DoMo Macropad
--------

This is a [ZMK](https://zmk.dev/) Firmware for [DoMo Macropad](https://github.com/MayTD/DoMo-Macro-Pad).

!["domo macropad"](https://i.imgur.com/Pl70dCi.png "domo macropad")

Just chug a 3.7v lipo battery to battery pins of micro controller, and use a [nice!nano](https://nicekeyboards.com/nice-nano/) or similar [compatible alternatives](https://github.com/joric/nrfmicro/wiki/Alternatives) and you'll get your macropad wireless in no time.

All features, including the EC11 Encoder, underglow RGB LED, and OLED display is working on this firmware. You can enable or disable individual features by altering or commenting out the flags in [domo.conf](./boards/shields/domo/domo.conf) file on your fork.

The firmware is prepared and tested using [Supermini NRF52840](https://github.com/joric/nrfmicro/wiki/Alternatives#supermini-nrf52840).


## How to install

* Fork this repository on your GitHub account
* Make sure the [GitHub Actions](https://github.com/features/actions) are enabled on your repository (should be enabled by default after your fork)
* Edit the [domo.keymap](./boards/shields/domo/domo.keymap) file to your liking.
* The "Actions" tab will run an automation and build the firmware automatically with your edits. After the build, a file (artifact) will be populated named `firmware.zip`. Download it and install it to your micro controller.
* You can now benefit from your upgraded micro controller and wireless features on your macropad.