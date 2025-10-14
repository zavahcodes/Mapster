# Mapster

**Version:** 1.3.9  
**Author:** Nevcairiel  
**Interface:** 3.3.0 (WotLK)  
**License:** All rights reserved

## Description

Mapster is a simple yet powerful addon for modifying the World of Warcraft world map. It allows you to control various aspects of the world map, change the map style, and configure different profiles for each of your characters.

## Main Features

### 🗺️ Map Control

- **Floating Window Mode**: The map no longer blocks the entire interface. You can move it freely around the screen
- **Two Display Modes**:
  - **Large Mode**: Full map with all quest panels
  - **Minimized Mode**: Compact version of the map
- **Free Positioning**: Drag the map anywhere on your screen
- **Persistence**: The map remembers its position and size

### ⚙️ Visual Customization

- **Adjustable Transparency**: 
  - Independent transparency control for large and minimized modes
  - Allows you to see the world environment while navigating the map
- **Customizable Scale**:
  - Adjust map size to your preference (10% - 200%)
  - Independent scales for large and minimized modes
- **Border Control**: Option to hide map borders
- **Strata Level**: Configure how "high" the map appears relative to other UI elements

### 📍 Coordinates Module

- **Player Coordinates**: Shows your current position on the map
- **Cursor Coordinates**: Shows the coordinates where your mouse is pointing
- **Adjustable Precision**: Configure how many decimals you want to see (0-2)
- **Real-Time Updates**: Coordinates update constantly

### 👥 Group Icons Module

- Shows the position of your group/raid members on the map
- Visual icons to easily identify your companions

### ⚔️ Battle Map Module

- Enhanced integration with battleground maps
- Optimized visualization during PvP

### 🌫️ FogClear Module

- Control over the "fog of war" on the map
- Option to reveal unexplored areas

### 🏰 Instance Maps Module

- Enhanced support for dungeon and raid maps
- Clearer navigation inside instances

### 🔍 Scaling Module

- Fine control over map zoom behavior
- Scale adjustments for different elements

### ✨ Other Features

- **Player Arrow Control**: Adjust the size of the arrow representing your position
- **Configurable Quest Objectives**:
  - Hide completely
  - Only blobs on world map
  - Blobs and full panels
- **Mouse Interactivity Control**: Option to make the map non-interactive (click-through)
- **Profiles**: Complete profile system using AceDB
  - Create different configurations for different characters
  - Copy configurations between profiles
  - Easily restore default values

## Library Integration

Mapster uses the following Ace3 libraries:
- **AceAddon-3.0**: Addon base framework
- **AceEvent-3.0**: Event system
- **AceHook-3.0**: Secure hooks system
- **AceDB-3.0**: Database and profiles
- **AceDBOptions-3.0**: Options interface for profiles
- **AceLocale-3.0**: Localization system
- **AceGUI-3.0**: Graphical interface widgets
- **AceConsole-3.0**: Console commands
- **AceConfig-3.0**: Configuration system

It also uses:
- **LibBabble-Zone-3.0**: Localized zone names
- **LibWindow-1.1**: Window position and size management

## Localization

Mapster is fully localized in the following languages:

- 🇺🇸 English (enUS)
- 🇩🇪 German (deDE)
- 🇪🇸 Spanish (esES/esMX)
- 🇫🇷 French (frFR)
- 🇰🇷 Korean (koKR)
- 🇷🇺 Russian (ruRU)
- 🇨🇳 Simplified Chinese (zhCN)
- 🇹🇼 Traditional Chinese (zhTW)

## Commands

The addon provides console commands to access the configuration (via AceConsole).

## Configuration

Access Mapster's configuration through WoW's interface options menu, or via console commands.

Configuration includes:

- General map settings
- Individual configuration for each module
- Profile management

## Modules

Mapster has a modular architecture. Each module can be enabled or disabled independently:

1. **Coords** - Coordinate system
2. **GroupIcons** - Group member icons
3. **BattleMap** - Battleground map enhancements
4. **FogClear** - Exploration fog control
5. **InstanceMaps** - Enhanced instance maps
6. **Scaling** - Advanced scale control

## Technical Notes

- **Interface Version**: 30300 (3.3.0 - Wrath of the Lich King)
- **SavedVariables**: MapsterDB
- The addon modifies the standard behavior of Blizzard's WorldMapFrame
- Disables Blizzard's "miniWorldMap" and "advancedWorldMap" modes to avoid conflicts
- The map is no longer subject to Blizzard's UIPanelLayout system

## Credits

- **Main Author**: Hendrik "Nevcairiel" Leppkes
- **Email**: h.leppkes@gmail.com
- **Curse Project**: mapster
- **Category**: Map

---

*This README describes the original features of Mapster addon version 1.3.9 before any custom modifications.*
