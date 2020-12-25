# The FORK :

## This fork is an attempt to make OAT code working on a Sanguinololu 1.3 (atmel1284p) + NEMA 17 + A4988 steppers

Sanguinololu desc : https://reprap.org/wiki/Sanguinololu

Sanguinololu features :
* Chip : atmel1284p
* 4x NEMA 17
* 4x A4988
* 2x temp inputs
* 2x heater or cooler outputs

Uploading firmware on sanguinololu :
- IDE : Visual Studio Code + PlatformIO plugin
- Interface : Using an Arduino UNO with "Arduino as ISP" code uploaded (I was unable to upload firmware using usb)
- Wiring :
* Arduino UNO : see "Arduino as ISP" Code for pin usage
* Sanguinololu : SPI pins (remove display before wiring !)

Geetech Nema 17 :
- 42SHD0034-20B
- 5V
- 1.0a
- 5,0Ω ± 10%
- 6,2mh ± 20%
- 300mN.m
- 12mN.m

## The FORKED project :

### The OpenAstroTracker:

![](https://i.imgur.com/5ENuuHv.jpg)

https://youtu.be/9MNLAIyqGoA

A cheap 3D printed tracking, GoTo and autoguiding mount for DSLR astrophotography.

Head over to [r/OpenAstroTech](https://www.reddit.com/r/OpenAstroTech/) for questions and stuff.

I you would be interested in buying the tracker as a printed kit, head over to [this site](https://openastrotech.com/products/)

####

For instructions, please see [this](https://www.instructables.com/id/OpenAstroTracker-a-DSLR-Tracking-GoTo-Mount-for-As/) Instructable 

A list of all guides can be found [here](https://www.reddit.com/r/OpenAstroTech/comments/gc4pmr/all_current_guides/)