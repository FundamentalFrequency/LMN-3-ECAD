# LMN-3-ECAD

![screenshot of PCB](https://github.com/stonepreston/LMN-3-ECAD/blob/main/.github/images/pcb_editor_screenshot.png)
![screenshot of PCB Rener](https://github.com/stonepreston/LMN-3-ECAD/blob/main/.github/images/pcb_rendering.png)

This repository contains the [KiCad 6](https://www.kicad.org/) project files for the LMN-3 PCB.

It is a part of the larger LMN-3 project, composed of the following
repositories:
- [LMN-3-DAW](https://github.com/stonepreston/LMN-3-DAW)
- [LMN-3-MCAD](https://github.com/stonepreston/LMN-3-MCAD)
- [LMN-3-ECAD](https://github.com/stonepreston/LMN-3-ECAD)
- [LMN-3-Firmware](https://github.com/stonepreston/LMN-3-Firmware)
- [LMN-3-Emulator](https://github.com/stonepreston/LMN-3-Emulator)


## Bill of Materials
| Description                | Model                            | Quantity | URL                                                                                            |
|----------------------------|----------------------------------|----------|------------------------------------------------------------------------------------------------|
| Diode                      | 1N4148                           | 49       | https://www.amazon.com/McIgIcM-1n4148-switching-Standard-Through/dp/B06XB1R2NK                 |
| Rotary Encoder             | EC11                             | 4        | https://www.amazon.com/WayinTop-Encoder-Potentiometer-Electronics-Projects/dp/B08728K3YB?psc=1 |
| Switch                     | 5 pin mechanical keyboard switch | 45       |                                                                                                |
| Joystick                   | COM-09032                        | 1        | https://www.sparkfun.com/products/9032                                                         |
| Keycaps                    | Any                              | 45       |                                                                                                |
| Microcontroller            | Teensy 4.1                       | 1        | https://www.pjrc.com/store/teensy41.html                                                       |
| Raspberry Pi               | Raspberry Pi 4                   | 1        |                                                                                                |
| Screen                     | Hyperpixel 4                     | 1        | https://www.sparkfun.com/products/15357                                                        |
| USB to Mini USB Cable      | CERRXIAN 9Inch                   | 1        | https://www.amazon.com/CERRXIAN-9Inch-Cable-Charge-2-Pack/dp/B07P9BRWS5                        |
| Raspberry Pi Power Adapter | 15W USB-C                        | 1        | https://www.raspberrypi.com/products/type-c-power-supply/                                      |

The LMN-3-DAW has been tested on the 4 GB Raspberry Pi 4 only. Additionally, the Hyperpixel 4 screen also comes in a non touch version. The LMN-3-DAW does not rely on any touch capability, but the design of the touch-based Hyperpixel 4 looks nicer than the non-touch version. The non-touch version is a little bit cheaper though if you would like to keep costs down. 

## Thanks
This project would not be possible without the following free and open source projects:
- [KiCad](https://www.kicad.org/)
- [Keyswitch Kicad Library](https://github.com/perigoso/keyswitch-kicad-library)

### Sources for Footprints, Symbols, 3-D Models, and Other Resources
#### Encoders (Alps EC11E09244AQ)
- [Product Page](https://www.mouser.com/ProductDetail/Alps-Alpine/EC11E09244AQ?qs=fMKjfF2mFohVUA4%2Ftyw7NQ%3D%3D)
- [Datasheet and Mechanical Drawing](https://tech.alpsalpine.com/prod/e/html/encoder/incremental/ec11/ec11e09244aq.html)
- [3-D Model](https://www.snapeda.com/parts/EC11E09244AQ/ALPS/view-part/?welcome=home&t=EC11E)

### Teensy 4.1
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
Licensed under the [CERN Open Hardware Licence Version 2 - Strongly Reciprocal](https://ohwr.org/cern_ohl_s_v2.txt) with the following exceptions:

The 3-D models located in `libraries/3D_models` are licensed under the [CC-by-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) license and were obtained from [SnapEDA](https://www.snapeda.com). 

Note that this repository includes the [keyswitch-kicad-library](https://github.com/perigoso/keyswitch-kicad-library) which requires the following notice be included:
```
The MIT License (MIT)

Copyright (c) 2019-2022 keyswitch-kicad-library contributors

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software. with the exception that
to the extent that the creation of electronic designs that use "Licensed Material"
can be considered to be 'Adapted Material', the copyright holder waives
this condition of the license with respect to these designs and any generated files
which use data provided as part of the "Licensed Material".

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
```
