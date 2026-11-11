# ⚓ Pentecenter Trade Booster
### Anno 117: Pax Romana Mod

[![Version](https://img.shields.io/badge/version-1.1.1-blue.svg)](https://github.com/peeweeh/anno-117-super-pertecenter/releases)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)
[![Anno 117](https://img.shields.io/badge/Anno%20117-Pax%20Romana-orange.svg)](https://www.anno-union.com)
[![Ko-fi](https://img.shields.io/badge/Ko--fi-Support%20Me-FF5E5B?logo=ko-fi&logoColor=white)](https://ko-fi.com/mrfixit027)
[![GitHub issues](https://img.shields.io/github/issues/peeweeh/anno-117-super-pertecenter)](https://github.com/peeweeh/anno-117-super-pertecenter/issues)
[![GitHub stars](https://img.shields.io/github/stars/peeweeh/anno-117-super-pertecenter?style=social)](https://github.com/peeweeh/anno-117-super-pertecenter)

## 📖 Overview
This mod focuses exclusively on buffing the civilian **Pentecenter** (GUID 37222) to excel as a fast, durable trade shuttle. Other Roman ships remain untouched (vanilla stats).

## 🚢 Current Pentecenter Stats (Modified)
- 📦 **Cargo Slots:** 9 (high throughput)
- ⚡ **Base Speed:** 30.0 (extreme speed for rapid route cycling)
- 🔄 **Acceleration:** 3 / **Deceleration:** 3
- 🔃 **Rotation Speed:** 50 (agile turns)
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
super-pertecenter/
├── modinfo.json
└── data/
    └── base/
        └── config/
            └── export/
                └── assets.xml
```

## ⚖️ Balance & Notes
- ⚡ Speed 30.0 is far above normal; retained per original user request.
- ❤️ High health (4000) ensures survival during trade routes without making the ship offensive.
- ⏱️ Low build time enables quick fleet scaling early.
- 🔒 No changes to costs, upkeep, or other ships to minimize side effects.

## 🔧 Adjusting Values (Optional)
Edit `assets.xml` and change properties under the single `<ModOp>` blocks for GUID 37222. Example: lower `<BaseSpeed>` or `<SlotCount>` for a more balanced experience.

## 🔍 Troubleshooting
- ❌ **No effect?** Ensure you built a new Pentecenter after enabling the mod.
- ⚠️ **XML error?** Validate closing tags and GUID quotes.
- 🔥 **Overpowered feel?** Reduce speed to 6–8 and health to ~1500.

For more help, [open an issue](https://github.com/peeweeh/anno-117-super-pertecenter/issues/new/choose) on GitHub.

## 🤝 Contributing

We welcome contributions! Whether it's bug reports, feature suggestions, or code improvements:

- 🐛 [Report a bug](https://github.com/peeweeh/anno-117-super-pertecenter/issues/new?template=bug_report.md)
- ✨ [Request a feature](https://github.com/peeweeh/anno-117-super-pertecenter/issues/new?template=feature_request.md)
- ⚖️ [Share balance feedback](https://github.com/peeweeh/anno-117-super-pertecenter/issues/new?template=balance_feedback.md)
- 🔧 [Report compatibility issues](https://github.com/peeweeh/anno-117-super-pertecenter/issues/new?template=compatibility_issue.md)

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for detailed guidelines.

## 📜 Version History

See [CHANGELOG.md](CHANGELOG.md) for detailed version history.

**Latest Release:**
- **v1.1.1** (2025-12-20): Speed stat corrected to 30.0 in description; workflow tweaks.
- **v1.1.0** (2025-11-20): Scope reduced to Pentecenter only; metadata updated.
- **v1.0.0** (2025-11-16): Original multi-ship enhancement (deprecated).

## 📚 Documentation

- 📋 [Product Requirements Document (PRD)](prd.md) - Design decisions and rationale
- 📜 [Changelog](CHANGELOG.md) - Detailed version history
- 🤝 [Contributing Guide](CONTRIBUTING.md) - How to contribute
- ⚖️ [License](LICENSE) - MIT License

## 🔗 Links

- 🐛 [Issue Tracker](https://github.com/peeweeh/anno-117-super-pertecenter/issues)
- 💬 [Discussions](https://github.com/peeweeh/anno-117-super-pertecenter/discussions)
- 📦 [Releases](https://github.com/peeweeh/anno-117-super-pertecenter/releases)

## 👏 Credits

Original concept and implementation by **mrfixit**.

Special thanks to the Anno modding community for tools and support.

---

## 📝 Changelog
- Latest: **1.1.1 (2025-12-20)** – Speed text corrected to 30.0; docs/workflow updated.
- Full history: see [CHANGELOG.md](CHANGELOG.md).

## 📝 mod.io Submission Guide

When uploading to mod.io, use these details:

**Name:** Pentecenter Trade Booster

**Summary:** Supercharged Pentecenter for rapid trade routes - 9 cargo slots, speed 30, health 4000, 10s build time

**Description:**
```html
<p style="text-align: center;"><a href="https://ko-fi.com/mrfixit027"><img src="https://storage.ko-fi.com/cdn/brandasset/kofi_button_red.png" alt="Ko-fi" width="200" /></a></p>
<p style="text-align: center;">⚠️ Found a bug? Report it on <a href="https://github.com/peeweeh/anno-117-super-pertecenter/issues">GitHub Issues</a> ⚠️</p>

<hr />

<p>Supercharge your <strong>Pentecenter</strong> trade ships for maximum efficiency! This mod buffs only the civilian Pentecenter (GUID 37222) - all other ships remain vanilla.</p>

<h3>🚢 PENTECENTER STATS</h3>

<ul>
<li><strong>📦 Cargo Slots: 9</strong> - Massive trade capacity for efficient routes</li>
<li><strong>⚡ Speed: 30.0</strong> - Lightning-fast route cycling (was ~3.0)</li>
<li><strong>❤️ Health: 4000</strong> - Survive pirate encounters while trading</li>
<li><strong>⏱️ Build Time: 10 seconds</strong> - Rapid fleet deployment</li>
<li><strong>🔧 Module Slots: 2</strong> - Standard customization options</li>
<li><strong>🔄 Enhanced Handling</strong> - Better acceleration, deceleration, and turning</li>
</ul>

<h3>✨ WHY THIS MOD ROCKS</h3>

<ul>
<li>Perfect for players who love efficient trade networks</li>
<li>Eliminates waiting for slow trade ships</li>
<li>Durable enough to survive incidental attacks</li>
<li>Quick to build when you need more capacity</li>
<li>Only affects Pentecenter - Trireme and Quinquireme stay vanilla</li>
<li>Save Compatible - Drop it in anytime</li>
<li>Mod Compatible - Clean ModOps, no conflicts</li>
</ul>

<h3>⚖️ BALANCE NOTES</h3>

<p><strong>This is intentionally overpowered</strong> for trade convenience. If it feels too strong:</p>
<ul>
<li>Speed can be reduced to 6-8 for more balanced gameplay</li>
<li>Cargo can be lowered to 6-7 slots</li>
<li>Health can be reduced to ~1500</li>
</ul>

<p>Just enable the mod and watch your trade routes fly! ⚡🚢</p>
```

**Tags:** ships, trade, pentecenter, overpowered, quality-of-life, naval, economy

**Maturity Rating:** Everyone

**File to Upload:** `super-pertecenter-v1.1.1.zip` (from GitHub Releases)

**Changelog:** See [CHANGELOG.md](CHANGELOG.md).

---

**Enjoy your supercharged trading fleet!** ⚓🚢