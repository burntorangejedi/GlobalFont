# Changelog

All notable changes to GlobalFont will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Planned Features
- Classic WoW support
- Wrath of the Lich King Classic support
- Cataclysm Classic support
- Font size adjustment options
- Export/Import font settings
- Favorite fonts feature

## [1.0.0] - 2025-12-27

### Added
- Initial release of GlobalFont
- Font selector UI with live preview
- Support for default WoW fonts
- LibSharedMedia-3.0 integration for additional fonts
- Slash commands `/gf` and `/globalfont`
- Persistent settings across sessions (SavedVariables)
- Apply button to set selected font globally
- Automatic font application on login
- Scrollable font list for large font libraries
- Visual selection highlighting
- Font names displayed in their respective font styles

### Features
- Changes all major WoW UI font objects
- Works with Blizzard UI and most addons
- Lightweight and focused on single purpose
- No dependencies required (LibSharedMedia optional)

### Known Issues
- Some UI elements may require a `/reload` for complete font application
- Custom addons with hardcoded fonts won't be affected

---

## Version History Format

Each version entry includes:
- **Added**: New features
- **Changed**: Changes to existing functionality
- **Deprecated**: Soon-to-be removed features
- **Removed**: Removed features
- **Fixed**: Bug fixes
- **Security**: Security improvements
