# Changelog

## How the Version Works
The version will look like this: vx.y.z

The respective number will increase if one of the changes below happen
- x (Major Change) is any major change like designing a new PCB
- y (Stencil Change) is any change that needs a new stencil
- z (Minor Change) is any minor change, like silkscreen

**Note:** Not every revision will be tested, the release name will indicate if it was. 
Only very small changes are allowed so they should work if the stencil change worked.

## v0.1.0
- Split the schematic into two different boards.
- Added support for BMI160 and BMM150 and removed support for other IMUs
- Designed a new PCB to be a stacked design
- Status: Mostly worked other than soldering issue with SCL not working

## v0.1.1
- Fixed INT1 track being too small
- Improved ground plane connections above IMU
- Moved ground further away from 3v3
- Status: Untested

## v0.1.2
- Added Aux label instead of j2
- Added missing 3d models
- Removed unused footprints
- Status: Untested

## v1.0.0
- New design for board
- Removed BMM150 and made BMI160 a module
- fixes issues
	-#1 Use module instead of soldering on bmi160 on main board
	-#2 0805 passives
	-#3 Make trace spacing bigger
	-#8 Add RST and GPIO 9 button onto board
- Moved every componet (except lion managment) to this board
- Added pushbutton power instead of switch

## v1.1.0
- Removed resistor from usb shield to GND
- Fixed LCSC# for 1K resistor
-PCB Ordered
