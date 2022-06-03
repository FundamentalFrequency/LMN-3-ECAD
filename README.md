# LMN-3-ECAD

![screenshot of PCB](https://github.com/stonepreston/LMN-3-ECAD/blob/main/.github/images/pcb_editor_screenshot.png)
![screenshot of PCB Rendering](https://github.com/stonepreston/LMN-3-ECAD/blob/main/.github/images/pcb_rendering.png)

This repository contains the [KiCad 6](https://www.kicad.org/) project files for the LMN-3 PCB.

It is a part of the larger LMN-3 project, composed of the following
repositories:
- [LMN-3-Build-Guide](https://github.com/stonepreston/LMN-3-Build-Guide)
- [LMN-3-DAW](https://github.com/stonepreston/LMN-3-DAW)
- [LMN-3-MCAD](https://github.com/stonepreston/LMN-3-MCAD)
- [LMN-3-ECAD](https://github.com/stonepreston/LMN-3-ECAD)
- [LMN-3-Firmware](https://github.com/stonepreston/LMN-3-Firmware)
- [LMN-3-Emulator](https://github.com/stonepreston/LMN-3-Emulator)
- [LMN-3-Keycaps](https://github.com/stonepreston/LMN-3-Keycaps)

If you would like to support the project, please consider becoming a [sponsor](https://github.com/sponsors/stonepreston).


## Bill of Materials
| Description                | Model                            | Quantity | URL                                                                                            |
|----------------------------|----------------------------------|----------|------------------------------------------------------------------------------------------------|
| Diode                      | 1N4148                           | 49       | https://www.amazon.com/McIgIcM-1n4148-switching-Standard-Through/dp/B06XB1R2NK                 |
| Rotary Encoder             | EC11                             | 4        | https://www.amazon.com/WayinTop-Encoder-Potentiometer-Electronics-Projects/dp/B08728K3YB?psc=1 |
| Switch                     | 5 pin mechanical keyboard switch | 45       |                                                                                                |
| Joystick                   | COM-09032                        | 1        | https://www.sparkfun.com/products/9032                                                         |
| Keycaps                    | Any                              | 45       |                                                                                                |
| Microcontroller            | Teensy 4.1                       | 1        | https://www.pjrc.com/store/teensy41.html                                                       |
| Arduino Header Strip                    |                            | 2      | https://www.amazon.com/gp/product/B07PKKY8BX?psc=1                 |
                                     

## Gerbers
Gerber files are available [here](https://github.com/stonepreston/LMN-3-ECAD/releases) if you would like to have a board house manufacture the PCB. 

## Thanks
This project would not be possible without the following free and open source projects:
- [KiCad](https://www.kicad.org/)
- [Keyswitch Kicad Library](https://github.com/perigoso/keyswitch-kicad-library)

### Sources for Footprints, Symbols, 3-D Models, and Other Resources
#### Encoders (Alps EC11E09244AQ)
- [Product Page](https://www.mouser.com/ProductDetail/Alps-Alpine/EC11E09244AQ?qs=fMKjfF2mFohVUA4%2Ftyw7NQ%3D%3D)
- [Datasheet and Mechanical Drawing](https://tech.alpsalpine.com/prod/e/html/encoder/incremental/ec11/ec11e09244aq.html)
- [3-D Model](https://www.snapeda.com/parts/EC11E09244AQ/ALPS/view-part/?welcome=home&t=EC11E)

#### Teensy 4.1
- [Product Page](https://www.pjrc.com/store/teensy41.html)
- [3-D Model](https://www.snapeda.com/parts/DEV-16771/SparkFun%20Electronics/view-part/?t=teensy)

#### Thumbstick (SparkFun COM-09032)
- [Product Page](https://www.digikey.com/en/products/detail/sparkfun-electronics/COM-09032/6823623)
- [Datasheet](https://media.digikey.com/pdf/Data%20Sheets/Sparkfun%20PDFs/COM-09032_Web.pdf)
- [3-D Model](https://www.snapeda.com/parts/COM-09032/SparkFun%20Electronics/view-part/?t=joystick)
- [Eagle Library](https://github.com/sparkfun/SparkFun-Eagle-Libraries)

#### Keyboard Switches (Keyswitch Kicad Library)
- [Footprints, Symbols, and 3-D Models](https://github.com/perigoso/keyswitch-kicad-library)

## License
Licensed under the  [CC-by-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) license.
