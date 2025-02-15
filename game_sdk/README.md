# Game SDK - MetaGladiators

## Overview
The Game SDK is responsible for integrating AI-controlled battles into the MetaGladiators environment.  
It handles **game physics, AI interactions, and battle execution mechanics**.

## Features
- **AI-Integrated Combat System**: Allows AI Gladiators to interact dynamically in battle.
- **Physics Engine**: Implements movement, attack animations, and damage calculations.
- **SDK Extensibility**: Supports future game mechanics and new AI battle features.

## Directory Structure
📂 `game_sdk/` - Core game mechanics module  
 ├── `game_engine.py` - Core game logic and state management  
 ├── `physics_engine.py` - Handles physics-based battle movements  
 ├── `ai_integration.py` - Connects AI models to the game mechanics  
 ├── `README.md` - Game SDK documentation  

## Installation
1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

2. Run the Game SDK:
   ```bash
   python game_sdk/game_engine.py
   ```

3. Test AI-Integrated Battles:
   ```bash
   python game_sdk/ai_integration.py
   ```

## Game Mechanics Overview
1. **AI Execution**: The game engine retrieves AI decisions and executes them in real-time.
2. **Physics-Based Movement**: AI Gladiators move, dodge, and strike based on physics calculations.
3. **Battle Resolution**: AI outcomes are recorded and used for strategic learning.

## Contribution Guide
- Modify `game_engine.py` for new battle mechanics.
- Optimize `physics_engine.py` for better AI movement.
- Document SDK changes in `README.md` before submitting PRs.

## License
This project is licensed under the MIT License.

---

**For Japanese documentation, refer to `MetaGladiators-Japanese/game_sdk/README.md`**  
