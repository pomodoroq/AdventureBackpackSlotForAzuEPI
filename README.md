# AdventureBackpackSlotForAzuEPI

Adds a dedicated Backpack slot for [AdventureBackpacks](https://thunderstore.io/c/valheim/p/Vapok/AdventureBackpacks/) using [AzuExtendedPlayerInventory](https://valheim.thunderstore.io/package/Azumatt/AzuExtendedPlayerInventory/).

This mod provides a compatibility layer to ensure only backpack items can be equipped in a dedicated slot. Intended for players who want clean inventory management and UI integration.

---

## Features

- Adds a new "Backpack" slot to the inventory UI
- Compatible with AdventureBackpacks items only
- Soft dependency on AzuExtendedPlayerInventory
- Lightweight

---

## Requirements

- [BepInExPack for Valheim](https://valheim.thunderstore.io/package/denikson/BepInExPack_Valheim/)
- [AzuExtendedPlayerInventory](https://valheim.thunderstore.io/package/Azumatt/AzuExtendedPlayerInventory/)
- [AdventureBackpacks](https://thunderstore.io/c/valheim/p/Vapok/AdventureBackpacks/)

---

## Installation

**With Thunderstore or r2modman:**
Install via UI.

**Manual:**
1. Install all dependencies above.
2. Drop the contents of the `.zip` into `BepInEx/plugins/`.

---

## Uninstall Warning

**Important:** Unequip your backpack before uninstalling this mod.  
If an item is left in the slot when the mod is removed, it may become inaccessible.

---

## Development

- Plugin ID: `com.pomodoroq.adventurebackpackslotforazuepi`
- Main class: `BackpackSlotForAdventureBackpacks.BackpackSlot`
- Soft-dependency logic via `API.IsLoaded()`

---

## License

This project is licensed under the [Creative Commons Attribution-NoDerivatives 4.0 International License](https://creativecommons.org/licenses/by-nd/4.0/).

You may use and share this mod freely, but you may not reupload it under a different name or author, or modify and redistribute it.
