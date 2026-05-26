# Contributing to AbyssalCore Drill

Thank you for your interest in contributing! 🎉

## How to Contribute

### Bug Reports
Open an issue using the **Bug Report** template. Always include:
- Subnautica 2 version
- Mod version
- `BepInEx/LogOutput.log`
- Steps to reproduce

### Feature Requests
Open an issue using the **Feature Request** template. Describe the gameplay impact and how it fits the mod's vision.

### Code Contributions
1. Fork & clone the repo
2. Set up BepInEx development environment ([guide](docs/DEV_SETUP.md))
3. Work on your feature in a dedicated branch
4. Write clean, commented C# code
5. Test on a fresh save and an existing save
6. Open a Pull Request with a clear description

### Translations
Translations live in `src/Localization/`. Copy `en.json`, rename it to your language code, translate the strings, and open a PR.

## Code Style
- C# standard conventions
- XML doc comments on all public methods
- No hardcoded strings — use the localization system

## Asset Contributions
Contact the author on Discord before working on 3D models or textures to avoid duplication.
