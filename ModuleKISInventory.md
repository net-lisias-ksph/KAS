#### `ModuleKISInventory`

This module add an inventory to the part. 

Sample module configuration with the default values :
```
MODULE
{
	name = ModuleKISInventory
	maxVolume = 1
	externalAccess = true
	internalAccess = true
	slotsX = 6
	slotsY = 4
	slotSize = 50
	itemIconResolution = 128
	selfIconResolution = 128
	openSndPath = KIS/Sounds/containerOpen
	closeSndPath = KIS/Sounds/containerClose
	defaultMoveSndPath = KIS/Sounds/itemMove
	helmetOnSndPath = KIS/Sounds/helmetOn
	helmetOffSndPath = KIS/Sounds/helmetOff
}
```

- `maxVolume`: Maximum volume of inventory. 
- `externalAccess`: Allow inventory access by right clicking on the part from outside (from EVA)
- `internalAccess`: Allow inventory access by right clicking on the part from inside (from vessel)
- `slotsX`: Number of slot on the horizontal axis.
- `slotsY`: Number of slot on the vertical axis.
- `slotSize`: Size of the slots.
- `itemIconResolution`: Resolution of the item's slot icon.
- `selfIconResolution`: Resolution of the part's icon.
- `openSndPath`: Open sound path of the inventory
- `closeSndPath`: Close sound path of the inventory
- `defaultMoveSndPath`: Default move sound path of items in the inventory
- `helmetOnSndPath`: Put on helmet sound path (kerbal only)
- `helmetOffSndPath`: Remove helmet sound path (kerbal only)