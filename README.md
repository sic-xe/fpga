# SIC/XE FPGA Design

This repository holds the source code for an implementation of the SIC/XE
architecture on the
[RealDigital Blackboard](https://www.realdigital.org/hardware/blackboard) FPGA
development board.

The aim of the project is to implement a SIC/XE machine, which can do any
operation in the SIC/XE specification, but also has a few additional features
(currently this is a wishlist):

- [ ] Read an object file from an SD Card and use that to execute a program
- [ ] Have predefined Device IDs and formats for all available Blackboard
peripherals, such as LEDs (e.g. D128 is LED0, writing 1 to the device turns the LED on)
- [ ] Allow running the program step by step (i.e. a debugger)
- [ ] Using advanced peripherals such as the accelerometer or temperature sensor
as normal devices
- [ ] Using the HDMI output to be able to display graphics on an external monitor
(equivalent to the virtual monitor in the simulator)
- [ ] Playing MIDI files through the audio output (potentiometer as a volume button)

## Prerequisites

The Blackboard has two revisions, Rev. B and Rev. D., which require different
XDC files.
This repository uses Rev. D's XDC file, so if you have a Rev B., use that file
as a base and configure it in the same way as the XDC file in this project.

- [Rev. B Master XDC](https://www.realdigital.org/downloads/17d8290752cdfb33f9312c8c1effc30d.txt)
- [Rev. D Master XDC](https://www.realdigital.org/downloads/2df60d5ff6c80ac8b0778ab97205f760.txt)

## Instructions

TODO

## License

The project is licensed under the [CERN-OHL-S-2.0](LICENSE) license.
