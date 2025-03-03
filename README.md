# 3D Multiplayer First-Person Shooter

A browser-based first-person shooter game built with Three.js that simulates multiplayer functionality.

![Game Screenshot](![image](https://github.com/user-attachments/assets/d72b6c14-88f7-4f21-983d-764cc30d02da))

## Features

### Core Gameplay
- **Complete 3D environment** rendered with Three.js
- **First-person camera** with mouse look controls
- **WASD movement** system with collision detection
- **Shooting mechanics** with projectile physics
- **Health and damage system** with respawn functionality
- **Ammunition management** with reloading mechanics

### Multiplayer Simulation
- Bot players that move around the map independently
- Kill/death tracking system
- Scoreboard to track player performance
- Player models visible to other players

### User Interface
- Health bar displaying current player health
- Ammo counter showing current and reserve ammunition
- Crosshair for aiming
- Kill/death statistics
- Interactive start and respawn screens
- Tab-accessible scoreboard

### Map & Environment
- Custom 3D environment with buildings and obstacles
- Dynamic lighting and shadow system
- Ground plane and skybox

## How to Play

1. **Setup**: Clone the repository and open `index.html` in a modern browser
2. **Start**: Enter your player name and click "Start Game"
3. **Controls**:
   - **W/A/S/D**: Move forward/left/backward/right
   - **Mouse**: Look around
   - **Left Click**: Shoot
   - **R**: Reload weapon
   - **Tab**: View scoreboard (hold)

## Technical Implementation

### Rendering
- Uses Three.js for 3D rendering
- Implements camera controls with pointer lock API
- Handles dynamic lighting and shadows

### Game Mechanics
- Bullet physics with collision detection
- Health and damage system
- Ammo management with reloading timer
- Death and respawn functionality

### Player Simulation
- Bot players with basic AI movement
- Player statistics tracking
- Score management

### Future Improvements

This project currently simulates multiplayer functionality locally. To implement true multiplayer, future development would include:

1. **Server Integration**: Implementing a WebSocket server for real-time communication
2. **State Synchronization**: Synchronizing player positions, actions, and game state
3. **Latency Compensation**: Adding prediction and reconciliation for smooth gameplay
4. **User Authentication**: Adding user accounts and persistent statistics

## Technical Requirements

- Modern browser with WebGL support
- JavaScript enabled
- Pointer lock API support

## License

MIT License - Feel free to use and modify for your own projects.

## Acknowledgments

- Three.js for the 3D rendering library
- Inspiration from classic FPS games
