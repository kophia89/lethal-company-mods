# 1.1.5
+ Updated mod description for latest update compatibility.
# 1.1.4
+ Added the Kitchen knife to the reserved melee weapon slot.
+ Added a config option to allow setting the amount of ammo slots you want to add. If purchasing slots is enabled, the price for each additional ammo slot will go up by 10. (Configurable)
+ **NOTE:** Currently, all reserved ammo slots will have their own item slot frame in the UI, and will NOT stack. I do have this on my TODO list, however!
# 1.1.3
+ Removing items from the reserved weapons slots in the config should now work properly.
# 1.1.2
+ Edited config descriptions to add the current items in each slot in case players want to remove them.
+ Added reminder in config descriptions about adding items, that translated items may need to be added to the list of additional items.
+ Changed default weapon slot priority to 100. (99 for ranged weapon slot if enabled) Priority order for my mods should remain unchanged.
+ Added current items in slot to the README.
# 1.1.1
+ Updated README
# 1.1.0
+ Adds support for ReservedItemSlotCore 2.0.0 features.
+ Weapon slot can now be purchased!
+ Item slot price can be adjusted in the config.
+ Item slot priority can now be adjusted in the config.
+ Like-wise, the ammo slot can also be purchased, and the price and priority can also be configured.
+ Items can be added to this reserved item slot in the config. This can be handy when adding variations of this item, or when adding an item's translated name to the slot.
+ Added a dedicated keybind to force toggle to the reserved weapon slot. You can rebind this keybind if you have the InputUtils mod enabled.<br>
Force toggling this slot will toggle this slot until you scroll off of it without needing to hold the Alt key. This will work even if you normally hold Alt to swap to your reserved hotbar.
# 1.0.8
+ Added support for the GoldenShovel/AustraliumShovel mod.
# 1.0.7
+ Fixed warnings when InputUtils is not enabled.
# 1.0.6
+ Fixed errors caused when equipping/unequipping a weapon if the reserved ammo slot was disabled in the config.
# 1.0.5
+ Added config entry to give melee weapons their own reserved item slot.
+ Possible fix for shotgun shells not going into the reserved ammo slot.
# 1.0.4
+ Changes to support ReservedItemSlotCore 1.8.9
+ Added reserved ammo slot. This slot appears on the left of the screen, rather than on the right.
+ Reserved ammo slot can be disabled in the config. If you're the host, this setting will sync to each non-host client.
+ The Reserved ammo slot can currently accept shotguns shells, and LethalThings' emergency flare ammo. (LethalThings is not required, and won't cause problems if not enabled)
# 1.0.3
+ Didn't update previous patch correctly.
# 1.0.2
+ Fixed a specific issue causing an error about index out of range.
# 1.0.1
+ Stability improvements when running this mod, but host does not.
+ Updated dependency for ReservedItemSlotCore 1.7.4
# 1.0.0
+ Initial release