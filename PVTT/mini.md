# Minis
Minis are the heart and soul of many RPGs, and the PVTT system allows you to organize, deploy, and interact with minis on the table easily. 

You may either rez a mini directly from your inventory, or you may allow the PVTT to manage them for you by dropping the object into your table’s inventory. Minis may also be rezzed from Lairs. (Please see the section on Lairs for more information.) 

## Rezzing From The Table
To rez from the table, go to the main menu and press the “Rezzing” button, and then the “Minis” button.  This will give you a list of minis that are in the tables inventory.  Simply select the mini that you would like to rez, how many of them you want to place on the table, and then click on the table where you want them to appear. The minis will rez at that location and automatically link themselves to the table. 

You may choose the color assigned to the minis from the Rezzing>Rez Color menu. You may change the color of a rezzed mini from its Utility menu.

If you’ve elected to rez more than 1 mini, they will have a letter appended to their name. For instance, if you rez 3 goblins from the table, you will see Goblin A, Goblin B and Goblin C.

## Linking
Minis must be linked to a table to operate. If you rez a mini directly from inventory, it will initially be in an unlinked state.  To link the mini to a table, simply click the mini. It will search for nearby tables and link itself to a table that it finds. If the mini finds multiple tables it will ask you which table it should link to. 

## Assigning Players
Each mini may only be controlled by the Game Master or the player that they are assigned to. By default, the player is the owner of the object. You may explicitly assign a player from the Set Player button on the Utilities menu. This will bring up a list of nearby avatars. Simply select the person who you would like to have control of the mini.

## Moving Around
To move a mini, simply click it and then select the location on the table that you would like it to move to. The mini will turn and move to the new location. To cancel a move, just click the mini again.

## Turning to Face
To change the direction your mini is facing, select Turn from mini’s main menu.  This will put the mini into Turning Mode, indicated by the word “Turning” appearing below the mini’s name.  Click on the table in the direction you would like them to face. To leave Turning Mode, click the mini again.

## Targeting
To put the mini into Targeting Mode, select Targeting from the main menu and then click on the table.  A Target object will be rezzed where you clicked, and then connected to the mini. Clicking on the table will move the target and turn your mini to face in that direction. 

The target will display the name of the mini that is targeting it, and the distance between them in map units (see Maps and Scenes below.) 

To leave Targeting Mode click on your mini a second time.

## Status Icons and Areas of Effect
A mini may be set to display a condition status icon or an area of effect.  Multiple status conditions may be set on a mini but only the last one set will be shown.

See the section on table customization below in order to add custom statuses and conditions.

### Conditions
A status may be toggled on and off from the Status menu.  Setting a status will cause a status icon to bubble up from the mini on the table.  The table comes preconfigured with saveral statuses.

<details>
<summary>Preconfigured Statuses</summary>
*Preconfigured Statuses*

| Status |
| --- |
| Blinded |
| Charmed |
| Deafened |
| Frightened |
| Grappled |
| Hidden |
| Incapacitated |
| Invisible |
| Paralyzed |
| Petrified |
| Poisoned |
| Prone |
| Restrained |
| Stunned |
| Unconscious |
</details>

### Status Markers
Some conditions are progressive, such as death saves or Exhaustion. Open the Statuses menu  from the Effects menu and select the status you’d like to change. A menu will appear that allows you to add or subtract a point from the status. A filled pip will appear above the mini for each point they are assigned.

### Area of Effect (AOE)
Minis and targets may display an Area of Effect indicator.  Select AOE from the mini’s menus and indicate how large the area should be. A ring will appear around the mini representing the AOE’s range.

## Other Features
### Name
Sets the name displayed above the Mini
### Topple
Lays the mini on its side.
### Resize/Footprint
Changes a Mini’s footprint. A mini’s footprint is the number of map grids it occupies and is used when autoscaling it to the map.  Most normal sized creatures have a footprint of 1x1, larger creatures may be 2x2, 3x3 or even 4x4 for something truly gigantic. 
### Version/Update
Displays the version number of all the scripts in the mini. Pressing Update will check with the table. If the table has newer versions of any of the scripts, they will be updated. It is recommended that after an update you save your mini back into the table’s inventory.
### Mini.config
The mini.config notecard contains values that are set whenever the mini is first rezzed and override any default values.  It consists of a series of name value pairs.  Some frequently used values are:

| Name | Type | Description |
| --- | --- | --- |
| `MINI.NAME` | String | The name displayed over the Mini’s head. |
| `MINI.COLOR` | String or Vector | The color applied to the mini. |
| `MINI.COLOR.LINK` | Number | The linkset link number that color should be applied to. |
| `MINI.COLOR.FACE` | Number | The face on the linked prim that color is applied to. |
| `MINI.FORWARD` | Vector | The forward vector for a mini used to determine which way to face.This is typically <0, -1, 0>
| `MINI.FOOTPRINT` | Vector | The minis footprint.  This is typically <1, 1, 0>.  |
| `MINI.PORTRAIT` | UUID | The portrait texture to use for Card and Token minis.  |
