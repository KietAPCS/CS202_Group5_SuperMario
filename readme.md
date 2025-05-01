# Super Mario Bros with AI Power

## Overview
This project is a modern implementation of the classic Super Mario Bros game with advanced AI features. Built using C++ and SFML, the game faithfully recreates the iconic platforming mechanics of the original while adding innovative AI-powered features.

## Features

### Classic Gameplay
- **Multiple Playable Characters**: Choose between Mario and Luigi, each with unique abilities:
  - **Mario**: Features higher jumping power and double jump ability
  - **Luigi**: More agile with specialized movement capabilities
- **Multiple Worlds**: Navigate through 3 distinct worlds with 3 levels each
- **Classic Enemies**: Battle familiar foes including:
  - Goombas
  - Koopas (normal and flying variants)
  - Bowser
  - Petey Piranha
  - Heriss
  - And more!
- **Power-ups and Collectibles**:
  - Mushrooms to grow in size
  - Health-restoring items
  - Coins to collect
  - Fire power-ups

### Game Mechanics
- **Physics-Based Movement**: Realistic physics for jumping, movement, and enemy interactions
- **Animation System**: Smooth character animations for all actions
- **Collision Detection**: Accurate hit detection for platforms, enemies, and power-ups
- **Level Map System**: Detailed level designs with various terrains and obstacles

### AI-Powered Features
- **AI Companion**: Chat with an AI assistant during gameplay
- **Intelligent Enemies**: Enhanced enemy behavior through AI algorithms
- **Adaptive Difficulty**: Game adjusts to your play style
- **Ollama Integration**: Uses the Ollama service for AI processing

### Additional Features
- **Leaderboard System**: Track high scores and compare with friends
- **Save Game Progress**: Continue your adventure from where you left off
- **Multi-level Boss Battles**: Strategic boss fights with unique mechanics
- **Moving Platforms**: Dynamic level elements that require timing and skill
- **Special Effects**: Visual effects for actions and abilities

## Technical Details

### Built With
- **C++**: Core programming language
- **SFML**: Simple and Fast Multimedia Library for graphics rendering
- **JSON**: For data storage and configuration
- **Ollama**: AI model integration

### Architecture
The game is built using an entity-component system with a mediator pattern for event handling. Key components include:
- **Game State Management**: Handle different states (menu, gameplay, pause)
- **Animation Component**: Manage sprite animations
- **Physics Engine**: Handle movement and collisions
- **Game Event Mediator**: Coordinate communication between game elements
- **Player Manager**: Handle character state and abilities
- **Level Manager**: Generate and manage level layouts
- **Audio System**: Handle game sounds and music

## Controls
- **Movement**: Arrow keys or WASD
- **Jump**: Space or W/Up
- **Run**: Left Control
- **Crouch** (when big): S/Down
- **Pause**: Escape

## Installation and Setup
1. Clone the repository
2. Ensure you have SFML libraries installed (version 2.0 or higher)
3. Open the solution file (`source.sln`) in Visual Studio
4. Build the solution
5. Run the executable

## Game Progress System
The game features a comprehensive save system that:
- Tracks completed levels
- Saves player state between sessions
- Records high scores for each level

## Contributing
This project was developed by CS202 Group 5. If you'd like to contribute, please fork the repository and submit a pull request.

## Future Enhancements
- Additional characters with unique abilities
- More worlds and levels
- Enhanced AI capabilities
- Multiplayer support
- Custom level editor

## Credits
Created by CS202 Group 5 as part of the second-year first-semester group project.

## License
This project is for educational purposes. All Mario-related characters and concepts are owned by Nintendo. This is a fan project with no commercial intent.