# Ender Dave Marlin 3D Printer Firmware

![GitHub](https://img.shields.io/github/license/marlinfirmware/marlin.svg)
![GitHub contributors](https://img.shields.io/github/contributors/marlinfirmware/marlin.svg)
![GitHub Release Date](https://img.shields.io/github/release-date/marlinfirmware/marlin.svg)
[![Build Status](https://github.com/MarlinFirmware/Marlin/workflows/CI/badge.svg?branch=bugfix-2.0.x)](https://github.com/MarlinFirmware/Marlin/actions)

<img align="right" width=175 src="buildroot/share/pixmaps/logo/marlin-250.png" />

## Marlin 2.0 Bugfix Branch

__Not for production use. Use with caution!__

## Parts
|                     |
| ------------        |
| Ender 3             |
| SKR v1.3            |
| TMC 2209            |
| E3D Volcano         |
| E3D Titan Extruder  |
| [Magnetic Bed Sheet](https://www.amazon.co.uk/gp/product/B07QQN8NXP/)  |
| Inductive Probe     |
| OctoPrint Raspberry Pi 4 4GB |
| [Over the top Passive Cooling Shell for Pi 4](https://www.amazon.co.uk/gp/product/B07VD5L1VY) |
| Noctua NF-A4x20 5v PWM 4 Pin

## Mods
|                     |
| ------------        |
| [Hero Me Gen 3 V6](https://www.thingiverse.com/thing:3291101)    |
| [HeroMeGen3 5015 Dual Fan](https://www.thingiverse.com/thing:3291101) |
| [Y Axis Tensioner](https://www.thingiverse.com/thing:3097972)    |
| [X Axis Tensioner](https://www.thingiverse.com/thing:2854971)    |
| [Ender 3 All-In-One Case](https://www.thingiverse.com/thing:3688967) |
| [Raspicam Mount](https://www.thingiverse.com/thing:3188580)      |

## TODO
|                     |
|------------         |
| BTT TFT E3 v3 Screen       |
| BTT Smart Filament Sensor |
| XY Linear Rails     |
| E3D Cyclops Dual Extrusion or Palette |
| Printer Enclosure   |
| Filament Dry Box    |
| Hotend LED's        |
| BTT Power Relay for Mains |

## Marlin Settings Enabled

* Unified Bed Leveling with 10 point grid  
* Level Corners to allow inital leveling  
* Adaptive Smoothing  
* Status Message Scrolling  
* Show Total E on LCD  
* Scroll Long Filenames  
* Babystepping  
* Linear Advance  
* Buffer size set to 64 for SD and USB  
* 24v  
* Monitor Driver Status  
* Hybrid Threshold  
* TMC Debug  
* PID Autotune Menu 
* Inductive Probe  
* Use of the probe for Z-axis homing  
* Extra Probing  
* LCD Bed Leveling  
* Z Safe Homing  
* EEPROM Settings  
* Nozzle Park  
* Print Counter  
* Individual Axis Homing  
* M600 Filament Change

## Credits

The current Marlin dev team consists of:

 - Scott Lahteine [[@thinkyhead](https://github.com/thinkyhead)] - USA &nbsp; [Donate](http://www.thinkyhead.com/donate-to-marlin) / Flattr: [![Flattr Scott](http://api.flattr.com/button/flattr-badge-small.png)](https://flattr.com/submit/auto?user_id=thinkyhead&url=https://github.com/MarlinFirmware/Marlin&title=Marlin&language=&tags=github&category=software)
 - Roxanne Neufeld [[@Roxy-3D](https://github.com/Roxy-3D)] - USA
 - Chris Pepper [[@p3p](https://github.com/p3p)] - UK
 - Bob Kuhn [[@Bob-the-Kuhn](https://github.com/Bob-the-Kuhn)] - USA
 - João Brazio [[@jbrazio](https://github.com/jbrazio)] - Portugal
 - Erik van der Zalm [[@ErikZalm](https://github.com/ErikZalm)] - Netherlands &nbsp; [![Flattr Erik](http://api.flattr.com/button/flattr-badge-large.png)](https://flattr.com/submit/auto?user_id=ErikZalm&url=https://github.com/MarlinFirmware/Marlin&title=Marlin&language=&tags=github&category=software)

## License

Marlin is published under the [GPL license](/LICENSE) because we believe in open development. The GPL comes with both rights and obligations. Whether you use Marlin firmware as the driver for your open or closed-source product, you must keep Marlin open, and you must provide your compatible Marlin source code to end users upon request. The most straightforward way to comply with the Marlin license is to make a fork of Marlin on Github, perform your modifications, and direct users to your modified fork.

While we can't prevent the use of this code in products (3D printers, CNC, etc.) that are closed source or crippled by a patent, we would prefer that you choose another firmware or, better yet, make your own.
