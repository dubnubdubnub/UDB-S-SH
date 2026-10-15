# Unified Daughterboard S Series

> **UDB-S-SH fork:** J2 is a JST-SH compatible side-entry header (XYECONN XY-SH1.0-4A61, LCSC C19271998)
> in place of the Molex Pico-EZmate 78171-0004. Pinout is unchanged (1 = 5V, 2 = D-, 3 = D+, 4 = GND), so it
> takes a 4-pin 1:1 JST SH cable (SHR-04V-S-B both ends). The opening faces away from the USB-C receptacle.
> The files under `production/` are still the upstream EZmate build and have not been regenerated.

![banner](https://github.com/Unified-Daughterboard/UDB-S/raw/main/assets/S1-Banner-Img.jpg)

## Introduction
The Unified Daughterboard Project is an open standard to unify the USB daughterboards used in custom mechanical keyboard projects.  
The Unified Daughterboard allows designers to easily implementing electrical protection via a tested proven PCB, and allows users to maintain and repair their keyboards in the future.  
  
For more details on the Unified Daughterboard project, see the [main website](https://unified-daughterboard.github.io/).


## S Series

The S1 variant was developed as an entirely new form factor from the older C3 version based on real-world production usage and designer input.

- "Wide and narrow" 40mm wide x 9mm deep x 1.6mm thick form factor
    - Avoids obstacles such as weights commonly found in custom keyboards
    - Mountable both right-side-up and upside-down
- 2 x M3 mounting points 
    - Fewer large screw taps reduce thread defect issues and assembly effort
- Easy and inexpensive to source via JLCPCB or similar
- Large DB corner radii which allow keyboard cases to be milled at a large inner radius
- ESD protection, overcurrent protection, overvoltage protection, shielding noise decoupling, and single-path grounding to chassis functionality
- New Molex Pico-EZmate Connector, replacing the JST-SH on previous versions
- 1:1 connector pinout to retain compatibility with existing PCBs


## Using the S series uDB in your design
Please [visit the docs](https://unified-daughterboard.github.io/) for detailed implementation references and notices.  


## Previews
![Render](https://github.com/Unified-Daughterboard/UDB-S/raw/main/assets/front.jpg)
![Render](https://github.com/Unified-Daughterboard/UDB-S/raw/main/assets/rear.jpg)


## Credits
- [Gondolindrim](https://github.com/Gondolindrim)
- [hineybush](https://hineybush.com/)
- [ai03](https://ai03.com/)
- [GEON](https://geon.works/)
- [Sleepdealer](https://sleepdealer.xyz)
- [Xelus](https://xelus.me)
- [James (AKB)](https://alchemistkeyboards.com/)
- [kkatano](https://github.com/kkatano)
- [ToastyStoemp](https://vwolf.be)
- [Upas](https://cannonkeys.com)

C3 Unified:
- [Wilba](https://wilba.tech)
- Xondat
- [aeryxz](https://github.com/aeryxz)
- [Maximillian](https://github.com/Maximillian)
