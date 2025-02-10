# 1 Fuji 2 Hawk 3 Nasubi

A strategic top-down action-collection game developed for Micro Jam 030: Dreams (December 28-30, 2024). The game combines bullet-hell elements with strategic item collection, where players compete against an AI opponent while managing their growing size and abilities.

## 🎮 Game Overview

Play as an Eggplant seeking to collect pieces of dreams while competing against a rival Hawk. Every action has consequences - as you collect more dreams, you grow larger but slower, and your own projectiles can become hazards after ricocheting off walls.

### Core Features

- **Strategic Bullet-Hell Gameplay:**
  - 8-directional movement system
  - Multi-purpose projectile mechanics
  - Size-based movement scaling
  - Competitive AI opponent

- **Unique Projectile System:**
  - Four simultaneous white projectiles from rotating points
  - Projectiles serve multiple purposes:
    - Stun rival NPC
    - Collect items
    - Counter enemy projectiles
  - Dynamic projectile transformation (white to black on wall collision)
  - Ricochet mechanics

- **Advanced Item System:**
  - Random location spawning
  - Dynamic movement patterns
  - Wall collision physics
  - Strategic scoring mechanics

## 🛠️ Technical Implementation

### Development Stack
- **Engine:** Unreal Engine 5.4.2
- **Architecture:** Blueprint-based systems with modular design
- **Asset Pipeline:** Custom sprite creation and AI-assisted background generation

### Key Systems

1. **Movement System:**
   - Implemented 8-directional movement
   - Dynamic speed scaling based on score
   - Collision handling with boundaries

2. **Projectile Management:**
   - Multi-point shooting system
   - State transformation logic
   - Collision detection and response
   - Ricochet calculations

3. **AI System:**
   - Target acquisition logic
   - Competitive behavior patterns

4. **Item System:**
   - Procedural spawn point generation
   - Movement vector calculations
   - Collision response

### Asset Development

- **Sprite Creation Pipeline:**
  - Created using Procreate (128x128px canvas)
  - Processed through Piskel for spritesheet formatting
  - Background removal via Pixlr Express
  - Damage variant generation

- **Background Assets:**
  - Generated using DALL·E
  - Post-processed with Pixlr Express
  - Themed around Japanese art style (Suibokuga)

- **Audio Implementation:**
  - AI-generated background tracks using Mubert
  - Integration of "Retro sounds" package
  - Dynamic audio system implementation

## 🚀 Setup & Installation

1. **Requirements:**
   - Windows-compatible system

2. **How to Play:**
   - Visit [game page on itch.io](https://negimakushi.itch.io/1-fuji-2-hawk-3-nasubi)
   - Download the game
   - Extract the zip file
   - Run the executable

For developers interested in the source code:
- Clone the repository from GitHub
- Requires Unreal Engine 5.4.2 or newer to open project files

## 🔍 Development Insights

### Challenges Overcome
- Implemented complex AI behavior systems
- Created dynamic projectile transformation mechanics
- Managed size-based movement scaling
- Developed efficient asset creation pipeline

### Technical Achievements
- Clean code architecture with modular systems
- Efficient asset management
- Smooth integration of multiple game systems
- Successful build packaging for Windows

## 🔗 Links

- [Play Game](https://negimakushi.itch.io/1-fuji-2-hawk-3-nasubi)
- [Source Code](https://github.com/NagareNegishi/Game-jam2)


## 👥 Credits

- **Lead Developer:** Nagare Negishi
  - Core system implementation
  - Asset creation and modification
  - Systems integration
  - Build management

- **Development Consultant:**
  - Game design input
  - Progress tracking
  - Quality assurance
