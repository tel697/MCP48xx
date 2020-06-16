# Arduino MCP48xx Library


## Description
This is a small and simple library to control the MCP48xx family of digital to analog converters (DACs) with an Arduino board.

Currently it only works with the MCP4822, MCP4812, MCP4802 DAC. (This fork tested with an MCP4822 and an STM32F104C8)

This version is modified for use with an STM32F104C8 "Blue Pill" board, running Roger Clarkes STM32duino core which can be found [here](https://github.com/rogerclarkmelbourne/Arduino_STM32).

The reason for a version specifically for this board is that it has three SPI ports.  This copy is set to use SPI2, the file is hardcoded and I'm sure a better programmer can add the ability to select the port from the example sketch. If you're like me and just about getting by, just edit the mcp48xx.h file.  I've annotated it so you can see the edits.


## Installation

You will need to install this manually, download the zip file and copy the files to the library folder.  If using an original arduino, you probably need the library this is forked from).


## Dependencies

This library depends on the standard [SPI](https://www.arduino.cc/en/Reference/SPI) library.


## Changelog

[Changelog](CHANGELOG.md)


## Licensing
The code in this project is licensed under MIT license (inherited from the original work by Steve Gkountouvas).
