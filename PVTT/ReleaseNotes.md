# Pallis Virtual Tabletop Release Notes

## Version 1.2: 
08/23
### New Features
+ Assignable Gamemaster
  - Gamemaster may be changed to be someone other than the owner of the table.
  - Table may be placed into group mode allowing anyone in a group to assume the role of Gamemaster
  - Sample object for remotely setting the Gamemaster.
+ Added a menu inteface to Fog.
+ Mini script enhancements
  - Add glow effect
  - Change skin

### Bug Fixes
+ Remove from the mini's menu did not remove the mini.

### Bug Fixes

## Version 1.1: Minor Enhancements and bug fixes
05/23
### New Features
+ New table initialization
  - Logo shown durring initializiation.
  - Progress bars are now displayed for all initialization sequences.
  - Better visual indication when initialiaztion has completed.
+ Support for "open" minis that may be controlled by any player.
+ Targets and Map Pins now show a moving indicator when in move mode.
+ The display face on rizers can now be changed from the menus.
+ Risers now display the map grid.
+ Card and Token portrait selection menus can now be nested
+ Auto increment name suffix when duplicating a mini.
+ New tokens

### Bug Fixes
+ Duplicated(shift-drag) objects linked to a table would not always automatically link to the correct table.
+ Would not show the Gamemaster after table rez/init.
+ Inital map settings were not correct after initialization.
+ When rezzing minis with no grid specified on the table they would commonly appear at a great distance away from the table.
+ When a rizer/platform was restored by a scene it could become confused and oscilate between configurations.
+ Refactored the linking code for minis and lairs.
+ If there were no immediate children, lairs would show an empty menu.
+ If a lair defines no factions do not show "All" menue.

## Version 1.0: Initial Release.
04/23
The inital release of the table!
