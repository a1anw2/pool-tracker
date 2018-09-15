# pool-tracker
Project looking at the integration of hardware with software to track pool/snooker positions and to investigate the opportunities that could present

## Direction

We are looking to explore, and learn along the way, what it would take to have a system that would read a real life pool/snooker table during game play, and then using a laser-pointer, project back onto the table.

Possible applications:

* Automatic game score
* Suggested shot angles
* Replay classic setups by positioning a laser to where balls should be replaced
* and anything else we think of along the way

## Problems to solve

We want to concentrate on solving the following two problems:

* Taking a photo of a standard pool/snooker table and processing it for current ball positions
* Direct a (low powered) laser (like you find in presentation pointers) to shine on any given spot on the table

## Hardware

We'll be using a standard Raspberry Pi 3 as well as:

* Raspberry Pi (https://www.amazon.com/gp/product/B07BC567TW/)
* 2x Servo's to position a laser pointer (https://www.amazon.com/gp/product/B01J40NPVW/)
* HD Camera (https://www.amazon.com/gp/product/B01MYUOQ0A/)

Our aim is to utilize JavaScript for as much of this project as possible.