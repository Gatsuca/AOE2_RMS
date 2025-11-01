# AOE2_RMS - Age of Empires 2 Random Map Scripts

A collection of custom random map scripts (RMS) for Age of Empires 2, created by Kayo. These maps offer unique gameplay experiences with dynamic seasonal variations, strategic resource placement, and innovative map designs.

## 📋 Table of Contents

- [Overview](#overview)
- [Maps](#maps)
- [Features](#features)
- [Installation](#installation)
- [Technical Specifications](#technical-specifications)
- [Compatibility](#compatibility)
- [Contributing](#contributing)

## 🎮 Overview {#overview}

This project contains three professionally crafted random map scripts that bring fresh strategic challenges to Age of Empires 2. Each map features:

- **Dynamic Seasonal Systems** - Maps change appearance and resources based on randomly selected seasons/biomes
- **Strategic Resource Placement** - Carefully balanced resource distribution for competitive gameplay
- **Multi-Game Mode Support** - Compatible with various game modes including Regicide and King of the Hill
- **AI Compatibility** - Optimized for AI players with proper map type information
- **Scalable Design** - Adapts to all map sizes from Mini (80x80) to Ludicrous (480x480)

## 🗺️ Maps {#maps}

### 1. Bay Battle

**Theme:** Forest map with naval bay warfare  
**Focus:** Land-sea combined arms combat  
**Key Features:**

- Naval bay in northeast corner with strategic resources
- Forest terrain with seasonal variations
- Fish resources for naval economy
- Multiple water depth levels (shallow, medium, deep)

### 2. Forest River

**Theme:** Forest divided by rivers  
**Focus:** River crossing and territorial control  
**Key Features:**

- Rivers separate team territories
- Seasonal water effects (ice in winter, shallow in other seasons)
- King of the Hill support with center island
- Balanced resource distribution across landmasses

### 3. Ruin Rumble

**Theme:** Central city ruins to fight over  
**Focus:** Urban warfare and resource control  
**Key Features:**

- Central ruined city with walls and buildings
- Multiple biome variations (Alpine, Desert, African, etc.)
- Special buildings (Trading Workshop, Castle Ruins)
- Strategic military building placement

### 4. Nomad Ruins

**Theme:** Central city ruins to fight over. Now in Nomad!
**Focus:** Urban warfare and resource control  
**Key Features:**

- Central ruined city with walls and buildings
- Multiple biome variations (Alpine, Desert, African, etc.)
- Special buildings (Castle Ruins)
- Strategic military building placement

## ✨ Features {#features}

### Seasonal/Biome System

Each map includes dynamic seasonal selection:

**Bay Battle:**

- Spring (25% chance) - Birch forests, flowers, sheep
- Summer (25% chance) - Mixed forests, cows
- Autumn (25% chance) - Autumn forests, turkeys
- Winter (25% chance) - Snow forests, goats

**Ruin Rumble, Forest River, Nomad Ruins:**

- 15+ biome variations including Alpine, Desert, African, Asian, Tropical, and Frozen
- Each biome affects terrain appearance, color correction, and civilization themes

### Resource Management

- **Starting Resources:** Balanced gold and stone near player bases
- **Far Resources:** Strategic resources requiring expansion
- **Special Resources:** Map-specific resources (bay fish, city ruins)
- **Food Sources:** Seasonal herdable animals and huntable wildlife

### Game Mode Support

- **Standard Play** - Classic random map gameplay
- **Regicide** - King and Castle placement
- **King of the Hill** - Center control objectives
- **Team Games** - Optimized team positioning

## 🚀 Installation {#installation}

1. **Download** the `.rms` files from this repository
2. **Place** the files in your Age of Empires 2 Random Maps folder:
   - **Steam:** `Steam\steamapps\common\AoE2DE\resources\_common\random-map-scripts\`
   - **Microsoft Store:** `Age of Empires II Definitive Edition\resources\_common\random-map-scripts\`
3. **Restart** Age of Empires 2
4. **Select** the maps from the Random Map dropdown in multiplayer or singleplayer

## ⚙️ Technical Specifications {#technical-specifications}

### Map Scaling

Some maps dynamically adjust based on map size, for example:

| Map Size | Dimensions | Player Land % | Circle Radius |
|----------|------------|---------------|---------------|
| Mini     | 80x80      | 98-99%        | 30%           |
| Small    | 144x144    | 96-99%        | 31%           |
| Medium   | 168x168    | 94-98%        | 32%           |
| Normal   | 200x200    | 92-96%        | 36%           |
| Large    | 220x220    | 91-95%        | 38%           |
| Huge     | 240x240    | 90-94%        | 40%           |
| Giant+   | 252x252    | 90-94%        | 40%+          |

### Performance Optimization

- Efficient terrain generation algorithms
- Optimized object placement systems
- Balanced clumping factors for natural appearance
- Smart resource distribution to prevent clustering

## 🎯 Compatibility {#compatibility}

- **Age of Empires 2: Definitive Edition** (Primary)
- **All Expansions:** Compatible with all DLC civilizations
- **Mod Support:** Works with most gameplay mods
- **Multiplayer:** Fully compatible with online play

## 🤝 Contributing {#contributing}

Contributions are welcome! If you'd like to improve these maps or add new features:

1. **Fork** the repository
2. **Create** a feature branch
3. **Test** your changes thoroughly
4. **Submit** a pull request with detailed description

### Development Guidelines

- Follow RMS scripting best practices
- Include comprehensive comments
- Test on multiple map sizes
- Ensure AI compatibility
- Maintain balance across all civilizations

---

**Enjoy your battles in these unique Age of Empires 2 landscapes!** 🏰⚔️
