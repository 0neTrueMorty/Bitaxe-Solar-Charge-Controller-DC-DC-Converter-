# Bitaxe-Solar-Charge-Controller-DC-DC-Converter
A 12V solar charge controller designed to power a bitaxe.

This PCB will be made in KiCad and include:

1) MPPT charge controller for 12 V systems. Amps TBD
2) Undervoltage Threshold cutoff to stop the battery from draining
3) 12V-5V converter to power the bitaxe.

The goal of this project is to make an all-in-one PCB to interface between a bitaxe and any COTS 12V battery and solar panel setup (likely in the 100-200W range). 

# design

1) regulator selection

I plan to run X1 20w bitaxe, but will design for 60w

60w/5v = 12a

TI TPS51375LVBHR chosen design was created using TI's WEBENCH Power designer. pdf of design report uploaded to important documents

2) MPPT selection

TI BQ24650RVAR chosen because of internet


