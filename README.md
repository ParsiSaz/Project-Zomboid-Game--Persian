<div align="center">

# 🧟 Project Zomboid | Persian Localization (پارسی‌ساز پراجکت زامبوید)
### *Official ParsiSaz Community Translation, Custom Fonts & Radio Subtitle Localization*

<br/>

[![ParsiSaz Portal](https://img.shields.io/badge/🌐_Documentation_Portal-parsisaz.github.io%2Fparsisaz-00f2fe?style=for-the-badge&logo=googlechrome)](https://parsisaz.github.io/parsisaz/)
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg?style=for-the-badge)](https://www.gnu.org/licenses/gpl-3.0)
[![Locale](https://img.shields.io/badge/Locale-fa__IR-emerald?style=for-the-badge)](#-project-structure)
[![Maintainer](https://img.shields.io/badge/Maintained_by-Danial_Pahlavan-blue?style=for-the-badge&logo=github)](https://github.com/DanialPahlavan)

</div>

---

## 📖 Overview
This repository contains the complete Persian localization package for **Project Zomboid** (by The Indie Stone), organized according to the **ParsiSaz 2026 Game Localization Architecture (L10N-STD-2026)**.

---

## 🗂️ Project Structure (L10N-STD-2026)

```
Project-Zomboid-Game--Persian/
├── loc/                           # Decoupled Core Localization Data
│   ├── fa-IR/                     # Standard Persian Lua string definitions
│   │   ├── UI_FA.txt              # User interface & menus
│   │   ├── ItemName_FA.txt        # All inventory items & weapons
│   │   ├── Recipes_FA.txt         # Crafting recipes & blueprints
│   │   ├── SurvivalGuide_FA.txt   # Complete survival handbook
│   │   └── DynamicRadio_FA.txt    # Radio broadcasts & emergency broadcasts
│   └── glossaries/                # Survival terminology glossary
├── game_assets/                   # Game Engine Drop-in Directory
│   └── media/lua/shared/Translate/FA/
├── HISTORY.md                     # Semantic Versioning Changelog
├── README.md                      # Project documentation
└── LICENSE                        # GNU General Public License v3
```

---

## 🚀 Installation Instructions

1. Download or clone this repository.
2. Copy the contents of `game_assets/media/` (or `FA/`) directly into your Project Zomboid folder:
   ```text
   <Project_Zomboid_Directory>/media/lua/shared/Translate/FA/
   ```
3. Launch Project Zomboid.
4. Go to **Options > Display / Language** and choose **Farsi / Persian (FA)**.
5. All UI, crafting recipes, moodles, and broadcasts will now appear in Persian.

---

## 🌐 Central Documentation & Bug Reports
For more details on engine hurdles, reverse engineering, and other games in the ecosystem:
👉 **[Open ParsiSaz Live Portal](https://parsisaz.github.io/parsisaz/)**
