# cátte — Package Processor

Make it less tedious to import or export only the things that you need.

## Features

### Export Processor
- **Smart Exclusions**: Automatically deselect assets based on type, extension, folder, or specific GUIDs
- **Type Filtering**: Toggle entire asset types on/off at once
- **Default Settings**: Configure which files should be off by default
- **Persistent Rules**: Save exclusion rules for consistent exports
- **Context Menu**: Right-click files for quick exclusion management

### Import Processor
- **Auto-Deselect Scripts**: Automatically deselects scripts during import (configurable)
- Reduces accidental script overwrites

### Settings Window
Access via `Tools > ⚙️🎨 kittyn.cat 🐟 > Package Processor > Settings`

- **Active**: Toggle whether settings affect exporting
- **Include Dependencies**: Set default state for dependency inclusion
- **Default Off Extensions**: File extensions to exclude by default
- **Default Off Folders**: Folder paths to exclude by default
- **Default Off Types**: Asset types to exclude by default
- **Default Off Assets**: Specific asset GUIDs to exclude by default

### Export Window Features
Right-click any file in the export window for:
- **Toggle Type**: Turn on/off all assets of the same type
- **Add/Remove Exclusions**: Quickly manage exclusion rules for assets, types, extensions, or folders

## Installation

Install via VRChat Creator Companion (VCC) or add to your Unity project's Packages folder.

**Requires**: Harmony library (for patching Unity's export/import windows)

## Requirements

- Unity 2019.4 or later
- Harmony (0Harmony.dll)

## License

MIT License - see LICENSE file for details
