# Pit-Box-Controller
A 3D printed leverless controller using the GP2040-CE firmware.

![PitBox_Photo](/pictures/PitBox_Photo1.jpg)
![PitBox_Photo](/pictures/PitBox_Photo2.jpg)

Parts Needed:
- Raspberry Pi Pico 
- 18 Choc v1 switches
- 4 M2.5 12mm screws
- 4 M2.5 threaded inserts
    - You could also screw directly into the plastic.
- 4 M2 4mm screws

Tools Needed:
- 3D printer
    - Must have a build plate of at least 220mm x 220mm
- Soldering iron (and associated tools, like solder, flux, etc.)

## Wiring
![Wiring_Guide](/pictures/Wiring_Guide.jpg)
- Black indicates ground. It does not matter how each switch is grounded or how many switches are wired to a ground pin, just that every switch has a route to ground.

## Firmware
The instructions for installing the firmware can be found at the official [GP2040-CE website](https://gp2040-ce.info/installation/).

## Printing
Buttons:
The arcade buttons printed were from a design by Long on [Printables](https://www.printables.com/model/148297-better-printed-arcade-button-kailh-choc-v1-low-pro). This is not required as any button design that are the standard 24mm and 30mm diameters and have Choc V1 stems work as well.
- This design in particular requires gluing the stems onto the keycap, but other designs may not need to do this.

Menu Buttons: 
The menu buttons were remixed from Long's design and follow the same dimensions as standard Choc V1 keyboard keycaps (16.5mm x 17.5mm), only with taller walls.
- These also have stems that must be glued on, but other designs can be used instead.

The rest of the parts can be printed as they are in their default orientations. The horizontal expansion in the slicer settings may have to be modified so that the switches and buttons fit properly.

## Assembly
![Assembly Render](/pictures/Assembly_Render.png) 


## License
Shield: [![CC BY-NC-ND 4.0][cc-by-nc-nd-shield]][cc-by-nc-nd] 

This work is licensed under a
[Creative Commons Attribution-NonCommercial-NoDerivs 4.0 International License][cc-by-nc-nd].

[![CC BY-NC-ND 4.0][cc-by-nc-nd-image]][cc-by-nc-nd]

[cc-by-nc-nd]: http://creativecommons.org/licenses/by-nc-nd/4.0/
[cc-by-nc-nd-image]: https://licensebuttons.net/l/by-nc-nd/4.0/88x31.png
[cc-by-nc-nd-shield]: https://img.shields.io/badge/License-CC%20BY--NC--ND%204.0-lightgrey.svg
