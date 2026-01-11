# 🩸 LP PvP Suite

> **A clean, fast, and competitive PvP HUD ecosystem for FiveM**
> Built for ESX / QBCore servers that want **clarity, performance, and style**.

---

<p align="center">
  <img src="https://github.com/user-attachments/assets/0aaf814b-134d-46bb-bed2-b1311be25fe1" width="70%" />
</p>

---

## 📦 Included Resources

| Resource           | Description                                    |
| ------------------ | ---------------------------------------------- |
| **lp_pvphud**      | Core PvP HUD (health, armor, ammo, match info) |
| **lp_leaderboard** | Live leaderboard with kills, deaths & ranking  |
| **lp_killfeed**    | Animated real-time kill feed                   |
| **lp_killstreak**  | Kill streak alerts & counters                  |

Each resource works **standalone** but is designed to feel like **one unified system**.

---

##  lp_pvphud

Minimal, competitive-focused HUD designed for PvP servers.

###  Features

* Health & armor bars
* Ammo display
* Match state awareness
* Clean typography
* Optimized for high-FPS combat

<p align="center">
  <img src="https://github.com/user-attachments/assets/80e01dba-e412-45be-90b0-3183213ac96e" />
</p>

---

##  lp_leaderboard

A modern leaderboard UI showing top PvP players in real time.

###  Features

* Live kill/death tracking
* Ranked player list
* Custom avatars / peds
* Weapon-based stats support
* Server-side SQL backed

<p align="center">
  <img src="https://github.com/user-attachments/assets/01f7666f-72b6-4a9f-a1b7-7105951aff60" width="90%" />
</p>

🎥 **Preview**

🔗 [https://github.com/user-attachments/assets/2537edcb-4229-4976-bb5a-91dbcaa7a807](https://github.com/user-attachments/assets/2537edcb-4229-4976-bb5a-91dbcaa7a807)

---

##  lp_killfeed

Stylish animated kill feed that keeps players informed without clutter.

###  Features

* Real-time PvP kill events
* Weapon icons support
* Clean fade & slide animations
* Team-aware coloring

<p align="center">
  <img src="https://github.com/user-attachments/assets/d1a13910-da67-41ae-82e9-c7af81121546" />
</p>

🎥 **Previews**

🔗 [https://github.com/user-attachments/assets/4bc61f10-3631-4624-906d-c83119cdad64](https://github.com/user-attachments/assets/4bc61f10-3631-4624-906d-c83119cdad64)

🔗 [https://github.com/user-attachments/assets/d90060bd-9999-4a13-9010-b8f226ac5509](https://github.com/user-attachments/assets/d90060bd-9999-4a13-9010-b8f226ac5509)

---

##  lp_killstreak

Reward players visually for dominating the battlefield.

###  Features

* Kill streak counter
* Animated popups
* Fully configurable streak thresholds
* Lightweight & event-driven

<p align="center">
  <img src="https://github.com/user-attachments/assets/e2c33d5e-61a3-4c52-ac14-af29cf068b8b" />
</p>

---

## ⚙️ Framework Support

✔ ESX
✔ QBCore
✔ ox_lib compatible
✔ oxmysql supported

---

## 🎨 Customization

* Colors & themes via CSS
* Toggle modules individually
* Adjustable screen positions
* Animation timing configs

---

## 📸 Screenshots & Media

soon ... 

---

##  Performance

* Event-based updates (no heavy loops)
* NUI optimized
* Safe for high-player PvP servers

---

> *Clean UI. Clear info. Pure PvP.*



# LP PvP Server Resource Pack

**Created by: remin**

A comprehensive FiveM server resource pack designed for PvP (Player vs Player) gameplay. This pack includes gamemodes, utilities, core framework resources, voice systems, inventory management, and various standalone scripts to create a complete PvP server experience.

![Server Overview]([cfx-default]/[test]/example-loadscreen/loadscreen.jpg)

---

## 📁 Project Structure

### Table of Contents
1. [Core Framework Resources](#core-framework-resources)
2. [PvP Gamemodes](#pvp-gamemodes)
3. [Game Utilities](#game-utilities)
4. [OX Framework Resources](#ox-framework-resources)
5. [Standalone Resources](#standalone-resources)
6. [Voice Systems](#voice-systems)
7. [Additional Resources](#additional-resources)

---

## 🎮 Core Framework Resources

### `[lp]/` - lp Framework Resources

#### **lp_core** 
- **Description**: Core framework resource for the server
- **Files**: 94 files (55 Lua scripts, 36 JSON locales)
- **Key Components**:
  - Bridge system (13 Lua files)
  - Client scripts (8 Lua files)
  - Server scripts (13 Lua files)
  - Configuration files (4 Lua files)
  - Shared utilities (9 Lua files)
  - Database SQL file
  - 36 locale files for internationalization
- **Purpose**: Provides core server functionality, player management, and framework integration

#### **lp_adminmenu**
- **Description**: Administrative menu system
- **Files**: 25 files (12 Lua scripts, 11 JSON locales)
- **Components**:
  - Client-side menu handlers (8 Lua files)
  - Server-side handlers (2 Lua files)
  - Configuration (1 Lua file)
  - 11 locale files
- **Purpose**: Admin tools for server management, player moderation, and administrative functions

#### **lp_chat_theme** 
- **Description**: Custom chat theme styling
- **Files**: 5 files (1 CSS, 1 JS, 1 Lua manifest)
- **Purpose**: Customizes the in-game chat appearance and functionality

#### **lp_density** 
- **Description**: Controls NPC and vehicle density in the game world
- **Files**: 28 files (23 YMAP files, 3 Lua scripts)
- **Components**:
  - Client-side density control
  - Configuration file
  - Stream files for map modifications
- **Purpose**: Manages population density for optimized PvP gameplay

#### **lp_radialmenu**
- **Description**: Radial menu system for quick actions
- **Files**: 22 files (7 Lua scripts, 13 JSON locales)
- **Purpose**: Provides a circular menu interface for player interactions

#### **lp_spawn**
- **Description**: Player spawn system
- **Files**: 10 files (4 Lua scripts, 4 JSON locales)
- **Purpose**: Handles player spawning, character selection, and spawn locations

---

## ⚔️ PvP Gamemodes

### `[scripts]/[gamemode]/` - Game Mode Scripts

#### **f4st-ffa**
- **Description**: Fast-paced Free-For-All gamemode
- **Files**: Multiple Lua scripts, HTML/CSS/JS UI, SQL database
- **Components**:
  - Client-side scripts (client.lua, functions.lua, hitmarker.lua, keybind.lua)
  - Server-side scripts (2 Lua files)
  - HTML/CSS/JS interface
  - 9 PNG images for UI elements
  - SQL database file
- **Features**: FFA gameplay with hitmarkers, kill tracking, and custom UI

![FFA UI Elements]([scripts]/[gamemode]/f4st-ffa/html/img/1.png)

#### **lp_duels**
- **Description**: 1v1 duel system
- **Files**: Client & server scripts, web interface
- **Components**:
  - Client scripts (4 Lua files)
  - Server scripts (4 Lua files)
  - Web interface with 76 files (72 PNG images, CSS, HTML, JS)
  - Import and locale files
- **Purpose**: Allows players to challenge each other to duels

#### **lp_ffa**
- **Description**: Free-For-All gamemode
- **Files**: Client/server scripts, HTML interface, SQL
- **Components**:
  - Client scripts (4 Lua files)
  - Server scripts (2 Lua files)
  - HTML/CSS/JS interface
  - 9 PNG images
  - SQL database file
- **Purpose**: Standard FFA gamemode with leaderboards

#### **lp_gungame**
- **Description**: Gun Game gamemode progression system
- **Files**: Client/server scripts, HTML interface
- **Components**:
  - Client scripts (2 Lua files)
  - Server script (1 Lua file)
  - Configuration file
  - HTML/CSS/JS interface
- **Purpose**: Progressive weapon-based gamemode

#### **pc_crosshair**
- **Description**: Custom crosshair system
- **Files**: Client script, HTML interface, 82 files total
- **Components**:
  - Client script
  - Configuration file
  - HTML interface with 70 PNG crosshair images
  - 7 TTF font files
  - CSS styling
- **Purpose**: Provides customizable crosshairs for PvP gameplay

---

## 🛠️ Game Utilities

### `[scripts]/[gameutil]/` - Utility Scripts

#### **lp_killfeed**
- **Description**: Kill feed display system
- **Files**: Client/server scripts, HTML interface
- **Components**:
  - Client script (1 Lua file)
  - Server script (1 Lua file)
  - HTML/CSS/JS interface
- **Purpose**: Displays kill notifications in real-time

#### **lp_killstreak** / **rm_killstreak**
- **Description**: Kill streak tracking system
- **Files**: Client script, HTML interface, README
- **Components**:
  - Client script
  - HTML interface
  - Documentation
- **Purpose**: Tracks and displays player kill streaks

#### **lp_leaderboard_v2**
- **Description**: Advanced leaderboard system
- **Files**: Client/server scripts, HTML interface, SQL
- **Components**:
  - Client scripts (3 Lua files)
  - Server script (1 Lua file)
  - HTML/CSS/JS interface
  - SQL database file
- **Purpose**: Tracks and displays player statistics and rankings

#### **lp_Loading** / **Sp_Loading**
- **Description**: Custom loading screen
- **Files**: Client script, web assets
- **Components**:
  - Client Lua script
  - Web files (HTML, MP3 audio, PNG images, CSS, JS)
- **Purpose**: Custom loading screen with audio and visuals

#### **lp_pvphud**
- **Description**: PvP HUD (Heads-Up Display)
- **Files**: Client/server scripts, HTML interface
- **Components**:
  - Client scripts (3 Lua files)
  - Server script (1 Lua file)
  - HTML/CSS/JS interface
- **Purpose**: Displays PvP-relevant information (health, armor, kills, etc.)

#### **lp_pvpmenu**
- **Description**: PvP menu system
- **Files**: Client/server scripts
- **Components**:
  - Client script (1 Lua file)
  - Server script (1 Lua file)
- **Purpose**: Main menu for PvP-related actions

#### **lp_revive**
- **Description**: Player revive system
- **Files**: Client/server scripts
- **Components**:
  - Client.lua
  - Server.lua
- **Purpose**: Handles player revival mechanics

#### **pvp_lobby**
- **Description**: PvP lobby system with dark/light mode
- **Files**: Client script, shared config, web interface
- **Components**:
  - Client script
  - Shared configuration
  - Web interface (TypeScript/TSX, CSS)
  - 21 web files
- **Features**: 
  - Dark mode support
  - Light mode support
  - Modern React-based UI

![PvP Lobby Dark Mode](https://cdn.discordapp.com/attachments/1279331408489484379/1323888970039296152/image.png)

![PvP Lobby Light Mode](https://media.discordapp.net/attachments/1279331408489484379/1323886607459418132/image.png)

#### **webiste**
- **Description**: Website/portfolio system
- **Files**: HTML, CSS, JavaScript
- **Components**:
  - index.html
  - styles.css
  - script.js
  - project-loader.js
  - projects-data.js
  - theme-test.html
  - README.md
- **Purpose**: Web-based project showcase

---

## 🔧 OX Framework Resources

### `[ox]/` - OX Framework Integration

#### **ox_doorlock**
- **Description**: Advanced door locking system
- **Files**: 55 files (23 JSON locales, 12 Lua scripts, audio files)
- **Components**:
  - Client-side door management
  - Server-side door control
  - Audio files for door sounds
  - 23 locale files
  - SQL database files
  - Web interface
- **Purpose**: Manages door locks, access control, and door states

#### **ox_fuel**
- **Description**: Fuel system for vehicles
- **Files**: 31 files (19 JSON locales, 10 Lua scripts)
- **Components**:
  - Client-side fuel management
  - Server-side fuel tracking
  - Station configuration
  - 19 locale files
- **Purpose**: Realistic fuel consumption and refueling system

#### **ox_inventory**
- **Description**: Advanced inventory system
- **Files**: 443 files (356 PNG item images, 41 Lua scripts, 29 JSON locales)
- **Components**:
  - Client inventory management
  - Server inventory handling
  - 27 module files
  - 356 PNG item images
  - 29 locale files
  - Web interface
- **Purpose**: Complete inventory system with item images and management

#### **ox_lib**
- **Description**: Core library for OX framework
- **Files**: 218 files (77 Lua scripts, 34 JSON locales, 33 TSX files)
- **Components**:
  - 48 import files
  - 27 resource files
  - Web interface (TypeScript/TSX)
  - 31 locale files
  - Font files
- **Purpose**: Provides core functionality and utilities for OX resources

#### **ox_target**
- **Description**: Interaction targeting system
- **Files**: Client/server scripts, web interface, 21 locale files
- **Components**:
  - Client-side targeting (11 Lua files)
  - Server-side handlers
  - Web interface (JS, CSS, HTML)
  - 21 locale files
- **Purpose**: Context-based interaction system

#### **oxmysql**
- **Description**: MySQL database integration
- **Files**: 11 files (3 JS files, 3 Lua scripts)
- **Components**:
  - JavaScript database handler
  - Lua integration
  - Logger system
  - Web UI
- **Purpose**: Database connection and query management

---

## 🎨 Standalone Resources

### `[standalone]/` - Independent Resources

#### **bob74_ipl**
- **Description**: Interior Prop Loader for GTA V DLCs
- **Files**: 137 files (116 Lua scripts, 13 YBN files, 2 YDR files)
- **Components**:
  - DLC support for:
    - After Hours (Nightclubs)
    - Agents (Airstrip, Base, Factory, Hangar, Office)
    - Bikers
    - Bounties
    - Casino
    - Cayo Perico
    - Chop Shop
    - Doomsday
    - Drug Wars
    - Executive
    - Finance
    - Gunrunning
    - Heists
    - High Life
    - Import/Export
    - Mercenaries
    - Money
    - Security
    - Smuggler
    - Tuner
  - Stream files for map modifications
  - Library files
- **Purpose**: Loads and manages interior props from various GTA V DLCs

#### **illenium-appearance**
- **Description**: Advanced character appearance system
- **Files**: 117 files (72 Lua scripts, 23 TSX files, 8 TypeScript files)
- **Components**:
  - Client scripts (26 Lua files)
  - Server scripts (18 Lua files)
  - Shared utilities (7 Lua files)
  - Web interface (React/TypeScript)
  - 16 locale files
  - 4 SQL files
- **Purpose**: Comprehensive character customization system

#### **informational**
- **Description**: Information display system
- **Files**: 2 Lua scripts
- **Components**:
  - Server script
  - Manifest file
- **Purpose**: Displays server information

#### **mana_audio**
- **Description**: Audio management system
- **Files**: 5 files (3 Lua scripts, 1 README)
- **Components**:
  - Client script
  - Server script
  - Documentation
- **Purpose**: Manages game audio and sound effects

#### **MugShotBase64**
- **Description**: Mugshot capture system with Base64 encoding
- **Files**: 11 files (2 Lua scripts, 2 Markdown docs, HTML files)
- **Components**:
  - Client script
  - HTML interface
  - Documentation
- **Purpose**: Captures player mugshots and converts to Base64

#### **Renewed-Weathersync**
- **Description**: Advanced weather synchronization system
- **Files**: 16 files (14 Lua scripts, 1 README)
- **Components**:
  - Client scripts (3 Lua files)
  - Server scripts (3 Lua files)
  - Compatibility files (5 Lua files)
  - Configuration files (2 Lua files)
- **Purpose**: Synchronizes weather across all players

#### **screencapture**
- **Description**: Screen capture utility
- **Files**: 9 files (3 JS files, 1 CSS, 1 HTML)
- **Components**:
  - Game scripts (6 files)
  - Web interface
- **Purpose**: Captures and processes game screenshots

#### **scully_emotemenu**
- **Description**: Advanced emote menu system
- **Files**: 376 files (179 YCD animation files, 85 YDR model files, 51 Markdown docs)
- **Components**:
  - Client scripts (11 Lua files)
  - Server scripts (2 Lua files)
  - Shared utilities (13 Lua files)
  - Stream files (289 files: animations, models, textures)
  - 7 locale files
  - Extensive documentation (50 Markdown files)
- **Purpose**: Comprehensive emote/animation system with extensive documentation

#### **vehiclehandler**
- **Description**: Vehicle handling and management system
- **Files**: 48 files (36 JSON locales, 6 Lua scripts, 4 PNG images)
- **Components**:
  - Client script
  - Server script
  - Data files (2 Lua files)
  - Module files
  - 36 locale files
  - 4 PNG images:
    - advancedrepairkit.png
    - cleaningkit.png
    - repairkit.png
    - tirekit.png
- **Purpose**: Manages vehicle repairs, cleaning, and handling

![Vehicle Handler Items]([standalone]/vehiclehandler/images/repairkit.png)

---



#### **pma-voice**
- **Description**: Proximity-based voice chat system
- **Files**: 51 files (17 Markdown docs, 14 Lua scripts, 6 JS file
