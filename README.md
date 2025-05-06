Firmware for PlastiCycle MK1
===================


Quick Information
===================
This firmware is a version of the Marlin-Mackerel from Filip Mulier (https://github.com/filipmu/Marlin-Mackerel)
This firmware was updated for control with geared stepper motors.  It is currently designed to support the RAMPS 1.4/1.5/1.6 with Smart LCD 2004. It can control the extruder motor, puller motor, Extruder heater (PID) with thermistor, winder motor, filament cooling fan and has input for a filament sensor.  The processes and menus have been adapted to control a filament extruder.  This code is currently in design, development, and testing, and so might not be ready for casual users.
This firmware is based on Marlin 3d Printer Firmware, but also has many original parts.

M Codes
=======

*  M303 - PID relay autotune S<temperature> sets the target temperature. (default target temperature = 150C)
