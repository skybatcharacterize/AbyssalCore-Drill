# 🌊 AbyssalCore Drill — Deep Drilling Mod for Subnautica 2

<div align="center">

![AbyssalCore Drill Banner](https://github.com/user-attachments/assets/d68445c4-a741-41e3-99c2-ec2741558812)

[![Thunderstore Downloads](https://img.shields.io/thunderstore/dt/YourName/AbyssalCoreDrill?style=for-the-badge&logo=thunderstore&logoColor=white&color=00d4ff)](https://thunderstore.io)
[![Nexus Mods Downloads](https://img.shields.io/badge/Nexus_Mods-Downloads-orange?style=for-the-badge&logo=nexusmods)](https://nexusmods.com)
[![GitHub Stars](https://img.shields.io/github/stars/YourName/AbyssalCore-Drill?style=for-the-badge&logo=github&color=gold)](https://github.com/YourName/AbyssalCore-Drill/stargazers)
[![GitHub Release](https://img.shields.io/github/v/release/YourName/AbyssalCore-Drill?style=for-the-badge&color=00ff88)](https://github.com/YourName/AbyssalCore-Drill/releases/latest)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)](LICENSE)
[![Subnautica 2](https://img.shields.io/badge/Subnautica_2-Compatible-teal?style=for-the-badge)](https://unknownworlds.com)

**The ultimate deep-sea drilling experience for Subnautica 2.**  
Mine rare ores from the ocean floor, unlock new biomes, and build the most powerful resource-extraction base ever seen on Planet 4546B.

[📥 Download Latest](https://github.com/YourName/AbyssalCore-Drill/releases/latest) • [📖 Wiki](docs/WIKI.md) • [🐛 Report Bug](https://github.com/YourName/AbyssalCore-Drill/issues) • [💬 Discord](#discord)

</div>

---

## 🎮 What is AbyssalCore Drill?

**AbyssalCore Drill** is a full-featured gameplay expansion mod for **Subnautica 2** that introduces an advanced **deep-sea drilling system**. Inspired by real-world deep-ocean mining technology, this mod lets you:

- 🔩 **Build modular drill rigs** on the ocean floor at depths up to 5,000m
- 💎 **Harvest 12 new rare minerals** found only in the deepest trenches
- ⚙️ **Upgrade your Prawn Suit** with the legendary **AbyssalCore Drill Arm** — the most powerful mining tool in the game
- 🏗️ **Expand your base** using Abyssal resources to craft advanced modules
- 🌑 **Explore new underground cave systems** opened by your drill operations
- 🧬 **Unlock a new tech tree** — the Deep Industrial Branch

> This mod is designed to feel like **vanilla Subnautica 2 content** — fully voice-line compatible, balanced, and lore-friendly.

---

## 📸 Screenshots

| Deep Drill Platform | AbyssalCore Drill Arm | New Minerals |
|---|---|---|
| ![Platform](assets/screenshot_platform.png) | ![Drill Arm](assets/screenshot_arm.png) | ![Minerals](assets/screenshot_minerals.png) |

---

## ✨ Features

### 🔧 AbyssalCore Drill Arm
A brand-new Prawn Suit arm module that replaces the standard drill arm:
- **3× faster** mining speed at crush-depth
- Mines **hardened geological formations** previously immune to standard drills
- Generates heat as a secondary resource for **Thermal Reactors**
- Compatible with all existing Prawn Suit upgrades

### 🏗️ Deep Drill Platform
A placeable structure for automated resource extraction:
- Deployable on flat terrain at any depth
- Connects to your base via **Resource Pipeline** (new buildable)
- 4 upgrade slots: Speed, Depth, Filter, Scanner
- Visual drill animation + particle effects + ambient audio

### 💎 12 New Minerals
| Mineral | Depth | Use |
|---|---|---|
| Abyssite | 2000m+ | Advanced hull plating |
| Thermalite | 3000m+ | Thermal reactor fuel |
| Voidcrystal | 4000m+ | Scanner upgrades, lighting |
| Pressium | 1500m+ | Pressure-resistant components |
| Deepfang Ore | 2500m+ | Drill arm reinforcement |
| Ironbloom | 1000m+ | Structural frames |
| Nullite | 4500m+ | Phase technology (endgame) |
| … and 5 more | — | — |

### 🌑 New Cave Systems
Drilling into specific geological formations reveals **procedurally-placed cave networks** containing:
- Unique flora & fauna
- Hidden resource caches
- Lore tablets expanding Subnautica 2's story

### 🔬 Deep Industrial Tech Tree
Unlock 18 new buildables and 9 new craftable items through progressive research:
```
Abyssite Discovery → Deep Platform Blueprint → AbyssalCore Arm → Deep Industrial Lab → Void Reactor
```

---

## 📥 Installation

### Recommended: Thunderstore Mod Manager
1. Install [Thunderstore Mod Manager](https://www.overwolf.com/app/Thunderstore-Thunderstore_Mod_Manager)
2. Search for **"AbyssalCore Drill"**
3. Click **Install** — dependencies handled automatically ✅

### Manual Installation
**Requirements:**
- Subnautica 2 (latest version)
- [BepInEx 6.x](https://github.com/BepInEx/BepInEx/releases) for Subnautica 2
- [Nautilus](https://github.com/SubnauticaModding/Nautilus) (modding API)

**Steps:**
```bash
1. Download the latest release from the Releases tab
2. Extract AbyssalCoreDrill.zip
3. Copy BepInEx/ folder into your Subnautica 2 game directory
4. Launch the game — the mod loads automatically
```

**Subnautica 2 game directory (default):**
```
Steam:   C:\Program Files (x86)\Steam\steamapps\common\Subnautica2\
Epic:    C:\Program Files\Epic Games\Subnautica2\
```

---

## ⚙️ Configuration

Edit `BepInEx/config/AbyssalCoreDrill.cfg` after first launch:

```ini
[Drilling]
DrillSpeed = 1.0          # Multiplier (0.5 – 3.0)
ResourceYieldMultiplier = 1.0
EnableCaveGeneration = true
MaxDrillPlatforms = 10    # Per save file

[Balance]
HardMode = false          # Harder resource requirements
ResourcesRequired = true  # false = creative/sandbox mode

[Visual]
DrillParticles = true
CaveGlowEffects = true
UIOverlay = true
```

---

## 🗺️ Roadmap

- [x] AbyssalCore Drill Arm (v1.0)
- [x] Deep Drill Platform (v1.0)
- [x] 12 New Minerals (v1.0)
- [x] New Cave Systems (v1.1)
- [x] Deep Industrial Tech Tree (v1.1)
- [ ] Multiplayer sync support (v1.2)
- [ ] Leviathan-class boss triggered by deep drilling (v1.3)
- [ ] 5 additional minerals + new biome: The Hollow Mantle (v1.4)
- [ ] Controller support & UI polish (v1.2)

---

## 🤝 Contributing

Contributions are welcome! Whether it's bug reports, translations, or new feature ideas.

1. Fork the repository
2. Create your branch: `git checkout -b feature/AmazingFeature`
3. Commit changes: `git commit -m 'Add AmazingFeature'`
4. Push: `git push origin feature/AmazingFeature`
5. Open a Pull Request

See [CONTRIBUTING.md](CONTRIBUTING.md) for detailed guidelines.

---

## 🐛 Bug Reports & Support

- **GitHub Issues** — [Open an issue](https://github.com/YourName/AbyssalCore-Drill/issues) with the provided template
- **Discord** — Join the [Subnautica Modding Discord](https://discord.gg/subnauticamodding) and find the `#abyssalcore-drill` channel
- **Logs** — Always include `BepInEx/LogOutput.log` when reporting bugs

---

## ❓ FAQ

**Q: Is this compatible with [other popular mod]?**  
A: AbyssalCore Drill is compatible with most major mods. Known conflicts are listed in [COMPATIBILITY.md](docs/COMPATIBILITY.md).

**Q: Does this work with existing saves?**  
A: Yes! Safe to add mid-playthrough. Removing mid-save is not recommended.

**Q: Will this get updates when Subnautica 2 updates?**  
A: Yes — I actively maintain this mod. Follow the repo to get notified.

**Q: Is multiplayer supported?**  
A: Partial support in v1.1. Full sync coming in v1.2.

**Q: Can I use assets from this mod in my own mod?**  
A: Ask first — open an issue or contact me on Discord.

---

## 📋 Compatibility

| Mod | Status |
|---|---|
| SeaTruck Upgrades | ✅ Compatible |
| Decorations Mod | ✅ Compatible |
| Alien Robot Mod | ✅ Compatible |
| SubConstructor | ⚠️ Minor visual conflicts |
| [Other Drill Mods] | ❌ Incompatible (same slot) |

---

## 📄 License

Distributed under the **MIT License**. See [LICENSE](LICENSE) for details.

**Assets** (3D models, textures, sounds) are licensed under **CC BY-NC 4.0** — free for non-commercial use with attribution.

---

## 🙏 Credits

- **Mod Author:** YourName
- **3D Models:** YourArtist
- **Sound Design:** YourAudioDev
- **Testing & QA:** [Community Testers — see CONTRIBUTORS.md]
- **Nautilus API:** [SubnauticaModding Team](https://github.com/SubnauticaModding/Nautilus)
- **Inspiration:** Unknown Worlds Entertainment — creators of the Subnautica universe

---

<div align="center">

**⭐ If you enjoy AbyssalCore Drill, please star this repo — it helps others find the mod!**

Made with 💙 for the Subnautica community

</div>
