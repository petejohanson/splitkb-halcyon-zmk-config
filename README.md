# Unofficial splitkb.com Halcyon ZMK Config

This is an unofficial config repo for the Halcyon controller and Kyria keyboard, using the 
still-in-development wired split support for ZMK. For details on that effort, see 
https://github.com/zmkfirmware/zmk/pull/2766

## Supported

* Normal ZMK use, including split
* ZMK Studio

## Not (Yet) Supported

The following features are not yet supported, but will be worked on incrementally:

* Cirque Halcyon Module
* Display Halcyon Module
* Encoder Halcyon Module
* RGB

## Not Planned

The following is *not* planned

* Support for dynamic central

Given that, this only works when plugging the left side into your computer.

## Usage Notes

To enter the bootloader, you will need to put `&bootloader` in a *layer* on each side of the keyboard,
to trigger that side to enter the bootloader. Double tapping reset does *not* enter the bootloader yet
in ZMK. Altenatively, hold the small white button on the Halcyon controller while plugging in or tapping
the tiny black side mount reset button.
