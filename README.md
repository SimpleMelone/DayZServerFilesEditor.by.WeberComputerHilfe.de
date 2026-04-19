# DayZ Server Files Editor

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![Electron](https://img.shields.io/badge/Electron-28.0+-9cf.svg)
![License](https://img.shields.io/badge/license-SEE%20LICENSE%20IN%20LICENSE-green.svg)
![Platform](https://img.shields.io/badge/platform-Windows-lightgrey.svg)

A comprehensive, all-in-one DayZ server configuration tool built with Electron and React. Edit loot tables, events, spawn points, weather, gameplay settings, and more with an intuitive interface.

## 🎯 Features

### Core Editors
- **Dashboard** - Server overview and file management
- **Server Config** - Edit serverDZ.cfg and basic settings
- **Globals Editor** - Edit types.xml, globals.xml with variable grouping
- **Types Editor** - Manage item types and configurations
- **Events Editor** - Edit events.xml with visual feedback

### Economy & Spawning
- **Economy Editor** - Edit economy.xml with preset management
- **Economy Core Editor** - Edit ce.xml (central economy)
- **Spawn Points Editor** - Visual spawn point management
- **Spawn Gear Editor** - Configure spawn loadouts
- **Spawnable Types Editor** - Manage spawnable item types
- **Random Presets Editor** - Configure random spawn presets

### Advanced Features
- **Custom Loadouts** - JSON-based custom spawn loadout system with dropdown selection
- **init.c Loadouts** - Edit init.c loadout configurations
- **Messages Editor** - Configure server messages
- **Ignore List Editor** - Manage ignore lists
- **Weather Editor** - Configure weather patterns
- **Gameplay Editor** - Fine-tune gameplay settings

### Tools
- **Map Editor** - Visual Chernarus+ map editor
- **Validator** - Validate XML files
- **Snapshots** - Save and restore configuration snapshots
- **Settings** - Application preferences

### Chernarus+ Optimization
- **Mission Selection** - Dedicated Chernarus+ mission folder selection
- **Visual Indicators** - Clear mission type identification
- **Optimized Editors** - All features tailored for Chernarus+ configuration files
## 🚀 Installation

### Windows (Recommended)
1. Download the latest release from [Releases](https://github.com/yourusername/DayZServerFilesEditor/releases)
2. Extract `DayZServerFilesEditor-v1.0.zip` to your desired location
3. Run `DayZServerFilesEditor.exe`
4. Create a desktop shortcut for easy access

### Getting Started
1. **Launch the Application** - Run `DayZServerFilesEditor.exe`
2. **Select Server Folder** - Browse to your DayZ server profile folder
3. **Select Mission** - Choose your Chernarus+ mission folder (if applicable)
4. **Start Editing** - Navigate to the desired editor tab

### Custom Loadout System
1. Navigate to **Custom Loadouts** tab
2. Use the **dropdown menu** for quick loadout selection
3. Click **"Next Loadout"** to cycle through available loadouts
4. Click **"Random Loadout 🎲"** for random selection
5. Edit loadout details in the main editor area
6. Save changes to apply to your server

### File Management
- **Auto-scan** - Automatically scans server folder for configuration files
- **Validation** - Built-in XML validation for error detection
- **Snapshots** - Save and restore configuration states
- **Backup** - Automatic backup before major changes

## ⚙️ Configuration

### Server Requirements
- DayZ Server 1.24+
- Windows 10/11
- 4GB RAM minimum
- 500MB disk space

### Application Settings
Configure application preferences in the **Settings** tab:
- Theme preferences
- Editor behavior
- File paths
- Auto-save intervals

### Key Technologies
- **Electron** - Desktop application framework
- **React** - UI library
- **esbuild** - Fast JavaScript bundler
- **fast-xml-parser** - XML parsing and validation
- **Tailwind CSS** - Utility-first CSS framework

## 🤝 Contributing

Contributions are welcome! Please follow these guidelines:

1. **Fork the repository**
2. **Create a feature branch** (`git checkout -b feature/AmazingFeature`)
3. **Commit your changes** (`git commit -m 'Add some AmazingFeature'`)
4. **Push to the branch** (`git push origin feature/AmazingFeature`)
5. **Open a Pull Request**

### Development Guidelines
- Follow existing code style
- Add comments for complex logic
- Test changes thoroughly
- Update documentation as needed
- Ensure Chernarus+ compatibility

## 📝 Changelog

### Version 1.0.0 (2024-04-19)
- **Initial Release**
- Complete Chernarus+ optimization
- Custom loadout dropdown menu
- Mission folder selection with visual indicators
- All core editors implemented
- XML validation and error detection
- Snapshot management system

## 🐛 Known Issues

- **Icon Display**: Custom icon may not appear in Windows Explorer due to Electron limitations. Use desktop shortcut for proper icon display.
- **File Locking**: Some files may be locked when the application is running. Close the app before manual file edits.

## 📄 License

This project is licensed under the terms specified in the [LICENSE](LICENSE) file.

Copyright © 2024-2026 [webercomputerhilfe.de](https://webercomputerhilfe.de)

## 🆘 Support

### Getting Help
- **Documentation**: Check this README and in-app tooltips
- **Issues**: Report bugs on [GitHub Issues](https://github.com/yourusername/DayZServerFilesEditor/issues)
- **Discussions**: Join discussions on [GitHub Discussions](https://github.com/yourusername/DayZServerFilesEditor/discussions)

### Contact
- **Email**: info@webercomputerhilfe.de
- **Website**: https://dayzserverfileseditor.webercomputerhilfe.de
- **Discord**: [Join our Discord](https://discord.gg/UgBqWyM)

## 🙏 Acknowledgments

- **Bohemia Interactive** - DayZ game and tools
- **Electron Team** - Desktop application framework
- **React Community** - UI library and ecosystem
- **DayZ Community** - Feedback and testing


**Built with ❤️ for the DayZ community by [webercomputerhilfe.de](https://webercomputerhilfe.de)**
