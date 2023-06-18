# Changelog

## How the Version Works
The version will look like this: vx.y.z

The respective number will increase if one of the changes below happen
- x (Major Change) is any major change like designing a new PCB
- y (Stencil Change) is any change that needs a new stencil
- z (Minor Change) is any minor change, like silkscreen

**Note:** Not every minor revision will be tested, they will be listed below. 
Only very small changes are allowed so they should work if the stencil change worked.

## v1.0.0
- Split this into its own kicad project
- Removed any components not for battery managment
- fixes issues
	-#2 0805 passives
	-#3 Make trace spacing bigger
	-#4 TP4056 gets hot at 500ma
	-#6 Verify that there is undervolt protection
