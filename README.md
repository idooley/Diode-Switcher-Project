# A Clipping Diode Selection Circuit
## _Do different clipping diodes matter in a Guitar Distortion/Overdrive circuit?_

This repo contains a rudimentary circuit board design that allows selection among 12 pairs of symmetric clipping diodes. The project was created in KiCad 6, and files are available here for anyone who wants to use them in their own projects.

Note, I have not yet assembled a working device from this design. 

## Why?
This circuit makes it easier to test various types of diodes in a Guitar Distortion Pedal. If this board is connected in place of the regular clipping diodes, it should be easy to rotate the switch and select among various alternatives.

## Features
- Designed for [this 12-way rotary switch](https://www.digikey.com/en/products/detail/e-switch/KC10A9-501NPS/1804492) based on its [drawings](https://spec_sheets.e-switch.com/specs/G527521.pdf). 
- Provides spaces for 12 pairs of diodes (or other components), with one end of each pair grounded, and the other end attached to one position on the switch.
- Gerber files and Drill files have been generated for anyone who wants to order their own PCBs from the cheap JLCPCB manufacturer. You might be able to get 10 boards there for $5 + shipping. If you prefer another manufacturer, you can generate appropriate gerbers from the KiCad project files also included in this repo.

## License

CERN Open Hardware Licence Version 2 - Permissive
