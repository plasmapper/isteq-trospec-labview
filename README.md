# LabVIEW Instrument Driver for ISTEQ TroSpec Spectrometers
Tested on custom TroSpec board with VID 0x04D8 and PID 0x89B6 on Windows 10.

## Requirements
LabVIEW 2015 and higher.

## Installation
1. Use [Zadig](http://zadig.akeo.ie/) to install the WinUSB device driver (recommended way of using [libusb on Windows](https://github.com/libusb/libusb/wiki/Windows#how-to-use-libusb-on-windows)).
2. Install the [VIPM package](https://www.vipm.io/package/plasmapper_lib_pl_isteq_trospec/)

## Features
1. Configure CCD period, gain, offset and frame acquisition.
2. Acquire frames in finite and continuous modes.
3. Save configuration to the flash memory. 

## Examples
### ISTEQ TroSpec.vi
Example VI that demonstrates all library features.
