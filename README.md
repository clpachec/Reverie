# Reverie

A cozy farming simulation game with tower adventure elements, where players tend a magical farm while exploring mysterious towers to rescue trapped souls and build a thriving village community.

## Game Overview

**Genre:** Farming Simulation + Tower Adventure  
**Engine:** Godot  
**Theme:** Dreams, wishes, and finding connection through understanding others

Players manage a magical farm in the village of Millhaven while exploring a mysterious tower that only they can see. Inside the tower, people are trapped within manifestations of their deepest wishes. Rescuing them brings new villagers to the community, creating deeper bonds and expanding the village's capabilities.

## Core Features

### 🌾 Farming System
- **Seasonal Crops:** 12 different crops across Spring, Summer, and Fall
- **Animal Care:** Chickens, sheep, and cows with breeding and affection systems
- **Daily Cycle:** 5am trader pickup, free-form daily activities, automatic sleep at 3am

### ⚔️ Tower Exploration
- **Real-time Combat:** Transform your arcane staff into various weapons
- **Character Rescue:** Save trapped souls to bring them into your village
- **Environmental Puzzles:** Use different staff forms to solve magical challenges

### 🏘️ Village Life
- **6 Core Villagers:** Each providing essential services and unique relationships
- **Relationship Building:** Daily interactions, gift-giving, and special events
- **Community Growth:** Rescued tower characters add new functions to the village

### 🔮 Magic System
- **Arcane Staff:** Single magical implement powered by ancestral pendant
- **6 Rune Forms:** Transform staff into farming tools and combat weapons
- **Progression:** 5-tier upgrade system with skill trees for each rune

## Technical Requirements

### Minimum Godot Version
- **Godot 4.x** (latest stable recommended)

### Target Platforms
- **Primary:** PC (Windows, macOS, Linux)
- **Future:** Mobile platforms consideration

## Getting Started

### Prerequisites
- Godot 4.x installed
- Basic familiarity with Godot project structure

### Installation
1. Clone this repository
```bash
git clone https://github.com/clpachec/Reverie.git
cd reverie
```

2. Open the project in Godot
```bash
# Open Godot and import the project.godot file
# Or use command line if Godot is in PATH
godot project.godot
```

3. Run the project
- Press F5 or click the Play button in Godot editor

## Project Structure

```
reverie/
├── assets/                 # Game assets (sprites, audio, etc.)
│   ├── sprites/
│   ├── audio/
│   └── fonts/
├── scenes/                 # Godot scene files
├── scripts/                # GDScript files
├── data/                   # Game data files
├── docs/                   # Documentation
│   └── game-design-document.md
└── project.godot          # Godot project file
```

## Development

### Core Systems Implementation Priority
1. **Basic Farming** - Crop planting, watering, harvesting
2. **Arcane Staff** - Tool transformation and basic combat
3. **Village NPCs** - Basic interaction and shop systems
4. **Tower Exploration** - Single area with combat and puzzles
5. **Progression** - Rune upgrades and skill trees
6. **Relationships** - Gift system and character events

### Code Style Guidelines
- Use PascalCase for class names and public methods
- Use snake_case for variables and private methods
- Add comments for complex game logic
- Follow Godot's built-in script templates

### Asset Guidelines
- **Sprites:** PNG format, consistent art style
- **Audio:** OGG format for music, WAV for short sound effects
- **Resolution:** Design for 1920x1080 base resolution

## Game Design Reference

For detailed game mechanics, systems, and design philosophy, see:
- [Game Design Document](https://docs.google.com/document/d/1gw-g0hAUNHeFooHR5G6ZrN-ohyu7ETGLoNPYEd45mwc/edit?tab=t.0#heading=h.qfd98g1r4s4i)

---
