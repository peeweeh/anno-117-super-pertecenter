# ⚓ Pentecenter Trade Booster
### Anno 117: Pax Romana Mod

## 📖 Overview
This mod focuses exclusively on buffing the civilian **Pentecenter** (GUID 37222) to excel as a fast, durable trade shuttle. Other Roman ships remain untouched (vanilla stats).

## 🚢 Current Pentecenter Stats (Modified)
- 📦 **Cargo Slots:** 9 (high throughput)
- ⚡ **Base Speed:** 24.0 (extreme speed for rapid route cycling)
- 🔄 **Acceleration:** 2 / **Deceleration:** 1.5
- 🔃 **Rotation Speed:** 60 (agile turns)
- 🔧 **Module Slots:** 2 (standard customization retained)
- ❤️ **Health:** 4000 (reinforced to survive incidental attacks)
- ⏱️ **Build Time:** 10 seconds (rapid deployment)

These values are intentionally powerful for trade convenience. If performance feels unbalanced in your playthrough, you may manually lower speed or cargo in `assets.xml`.

## 📥 Installation
1. 📂 Locate your Anno 117 mods folder: `Documents/Anno 117/mods/`
2. 📋 Copy the entire `super-ships` folder into the mods directory
3. 🎮 Launch Anno 117
4. ✅ Ensure the mod is active in the Mod Manager (if present)
5. 🚢 Build new Pentecenters (existing ships keep old stats)

## 🔒 Unchanged Content
- ⚓ **Trireme** (37223): Vanilla
- ⚓ **Quinquireme** (37224): Vanilla
- 💰 Asset pools and advanced cost/maintenance structures are not modified.

## 📁 File Structure
```
super-ships/
├── modinfo.json
└── data/
    └── base/
        └── config/
            └── export/
                └── assets.xml
```

## ⚖️ Balance & Notes
- ⚡ Speed 24.0 is far above normal; retained per original user request.
- ❤️ High health (4000) ensures survival during trade routes without making the ship offensive.
- ⏱️ Low build time enables quick fleet scaling early.
- 🔒 No changes to costs, upkeep, or other ships to minimize side effects.

## 🔧 Adjusting Values (Optional)
Edit `assets.xml` and change properties under the single `<ModOp>` blocks for GUID 37222. Example: lower `<BaseSpeed>` or `<SlotCount>` for a more balanced experience.

## 🔍 Troubleshooting
- ❌ **No effect?** Ensure you built a new Pentecenter after enabling the mod.
- ⚠️ **XML error?** Validate closing tags and GUID quotes.
- 🔥 **Overpowered feel?** Reduce speed to 6–8 and health to ~1500.

## 📜 Version History
- **v1.1.0:** Scope reduced to Pentecenter only; metadata updated.
- **v1.0.0:** Original multi-ship enhancement (deprecated).

## 👏 Credits
Original concept and implementation by **mrfixit**.