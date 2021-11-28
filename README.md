# Neptune CAN Toolboard

A small controller board designed to be used on a 3D printer as well as a SMD Pick and Place (PNP) machine.
It is designed to be used with Klipper firmware using CAN bus or USB connection.
Using CAN bus is it possible to chain many board using a pair of twisted wires for data and power.
It is also a good solution to simplify the toolhead wiring as only one cable is needed.

## Features:

* STM32F103 72MHz 32bits ARM MCU
* CAN bus
* USB (micro USB type B connector)
* 3x stepstick drivers with UART communication (with full diagnostics and control)
* 3x 5V powered inputs (endstop, filament runout sensor or whatever)
* 2x thermistor inputs (2.2k pullup resistor for PT1000 support)
* 3x MOSFET outputs (with freewheeling diode) - up to 5A
* 1x BL Touch connector
* 1x port for accelerometer connection for input shaping (no onboard chip as keeping the accelerometer as close to the nozzle is better)
* LEDs (Power, mosfet outputs & Activity)
* Debug port with SWD, NRST and BOOT0
* Components choosen for high-temp environnement (up to 85°C)

## Getting started:

To be defined


## Attribution

This board was designed from scratch but inspired by the [Huvud] and [TurboCAN] boards.

[Huvud]: https://github.com/bondus/KlipperToolboard
[TurboCAN]: https://github.com/henrikssn/TurboCAN

## License:
All included files are licensed under the [GNU GPL-3 license].

[GNU GPL-3 license]: https://www.gnu.org/licenses/gpl-3.0.html

