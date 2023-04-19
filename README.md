# ExtendedPlayerInventoryPlus
Some edits to the [original ExtendedPlayerInventory](https://github.com/aedenthorn/ValheimMods/tree/master/ExtendedPlayerInventory).

Edits:
```[Toggles]

## Number of extra ordinary rows.
# Setting type: Int32
# Default value: 0
ExtraRows = 5

[ZCurrentPositions]

Quick Access: Changed the location of Quick Slots to be next to the Buff icon (dynamically configured according to your game resolution)

## Current X of Quick Slots
# Setting type: Single
# Default value: 9999
quickAccessX = quickAccessX.Value = hudRoot.Find("healthpanel").GetComponent<RectTransform>().anchoredPosition.x + 170;

## Current Y of Quick Slots
# Setting type: Single
# Default value: 9999
quickAccessY = quickAccessY.Value = hudRoot.Find("healthpanel").GetComponent<RectTransform>().anchoredPosition.y - 1203;
```
