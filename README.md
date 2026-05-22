# Programmed Games

A collection of classic games built using C++ with SFML graphics library. This repository contains five fully functional games showcasing various game development concepts and mechanics.

## Language
- **C++** - 100%

## Games Included

### 1. 🌳 Timber Man Game
A fast-paced tree-chopping game where players must avoid dangerous branches.

**Features:**
- Dynamic branch falling mechanics
- Bee enemies that must be dodged
- Progressive difficulty levels
- Score tracking system
- Sound effects and animations

**Files:**
- `Timber.cpp` - Main game implementation
- `Reference.cpp` - Reference code
- `Test.cpp` - Test utilities

**Assets:**
- Graphics: `axe.png`, `background.png`, `bee.png`, `branch.png`, `cloud.png`, `log.png`, `player.png`, `rip.png`, `tree.png`, `tree2.png`
- Font: `KOMIKAP_.ttf`
- Sound Effects: `chop.wav`, `death.wav`, `out_of_time.wav`

---

### 2. 🏓 Pong Game
A classic two-player Pong implementation with arcade-style gameplay.

**Features:**
- Two-player gameplay
- Ball physics and collision detection
- Bat movement controls
- Score tracking
- Digital-style font rendering

**Files:**
- `Pong.cpp` - Main game engine
- `Ball.cpp / Ball.h` - Ball class and physics
- `Bat.cpp / Bat.h` - Bat/paddle implementation
- Compiled executable: `a.out`

**Assets:**
- Fonts: `DS-DIGI.TTF`, `DS-DIGIB.TTF`, `DS-DIGII.TTF`, `DS-DIGIT.TTF`
- Font info: `DIGITAL.TXT`

---

### 3. 🧟 Zombie Arena Game
An intense zombie survival shooter with multiple enemy types and power-ups.

**Features:**
- Wave-based enemy spawning
- Multiple zombie types (Chaser, Bloater, Crawler)
- Power-up system (health, ammunition)
- Weapon mechanics with ammunition tracking
- Crosshair targeting system
- Player movement and collision detection
- Sound-based feedback system

**Code Files:**
- `ZombieArena.cpp` - Main game implementation
- `Player.cpp` - Player class implementation
- `Compiled executable: `a.out`

**Graphics Assets:**
- Player: `player.png`
- Enemies: `chaser.png`, `bloater.png`, `crawler.png`
- Pickups: `ammo_pickup.png`, `ammo_icon.png`, `health_pickup.png`
- Environment: `background.png`, `background_originalsize.png`, `background_sheet.png`
- Effects: `blood.png`
- UI: `crosshair.png`, `sample.png`

**Sound Effects:**
- `shoot.wav` - Weapon firing sound
- `hit.wav` - Impact sound
- `reload.wav` - Magazine reload sound
- `reload_failed.wav` - Empty magazine click
- `pickup.wav` - Item collection sound
- `powerup.wav` - Power-up activation
- `splat.wav` - Zombie death sound

---

### 4. 🚗 Car Dodging Game
A driving game where players must dodge incoming traffic while navigating the road.

**Features:**
- Player car controls
- Enemy car AI and spawning
- Collision detection
- Score system based on cars dodged
- Dynamic difficulty progression

**Code Files:**
- `Main.cpp` - Main game implementation
- `Car.h` - Base car class
- `PlayerCar.h` - Player vehicle class with controls
- `EnemyCar.h` - Enemy vehicle class with AI
- Compiled executable: `a.out`

**Assets Directory:**
- `Code Files/Assets/` - Game assets location

**Output Screenshots:**
- 5 gameplay screenshots demonstrating various game states

---

### 5. 🐦 Flappy Bird Game
A classic Flappy Bird implementation where players navigate through pipes.

**Features:**
- Bird physics and gravity simulation
- Pipe obstacle generation
- Collision detection
- Score tracking
- High score persistence (saved to `HighScore.txt`)
- Game state management

**Code Files:**
- `Main.cpp` - Main game implementation
- `Bird.h` - Bird class with physics
- `Pipe.h` - Pipe obstacle class
- `HighScore.txt` - High score storage
- Compiled executable: `a.out`

**Assets Directory:**
- `Code Files/Assets/` - Game assets location

**Output Screenshots:**
- 6 gameplay screenshots showing different game scenarios

---

## Repository Structure

```
Programmed-Games/
├── README.md
├── LICENSE (MIT License)
├── Timber Game/
│   ├── Timber.cpp
│   ├── Reference.cpp
│   ├── Test.cpp
│   ├── a.out
│   ├── font/
│   │   └── KOMIKAP_.ttf
│   ├── graphics/
│   │   ├── axe.png
│   │   ├── background.png
│   │   ├── bee.png
│   │   ├── branch.png
│   │   ├── cloud.png
│   │   ├── log.png
│   │   ├── player.png
│   │   ├── rip.png
│   │   ├── tree.png
│   │   └── tree2.png
│   └── sound/
│       ├── chop.wav
│       ├── death.wav
│       └── out_of_time.wav
├── Pong Game/
│   ├── Pong.cpp
│   ├── Ball.cpp
│   ├── Ball.h
│   ├── Bat.cpp
│   ├── Bat.h
│   ├── a.out
│   └── font/
│       ├── DIGITAL.TXT
│       ├── DS-DIGI.TTF
│       ├── DS-DIGIB.TTF
│       ├── DS-DIGII.TTF
│       └── DS-DIGIT.TTF
├── Zombie Arena Game/
│   ├── ZombieArena.cpp
│   ├── Player.cpp
│   ├── graphics/
│   │   ├── ammo_icon.png
│   │   ├── ammo_pickup.png
│   │   ├── background.png
│   │   ├── background_originalsize.png
│   │   ├── background_sheet.png
│   │   ├── bloater.png
│   │   ├── blood.png
│   │   ├── chaser.png
│   │   ├── crawler.png
│   │   ├── crosshair.png
│   │   ├── health_pickup.png
│   │   ├── player.png
│   │   └── sample.png
│   ├── sound/
│   │   ├── hit.wav
│   │   ├── pickup.wav
│   │   ├── powerup.wav
│   │   ├── reload.wav
│   │   ├── reload_failed.wav
│   │   ├── shoot.wav
│   │   └── splat.wav
│   └── .vscode/
├── Car Dodging Game/
│   ├── Code Files/
│   │   ├── Main.cpp
│   │   ├── Car.h
│   │   ├── PlayerCar.h
│   │   ├── EnemyCar.h
│   │   ├── a.out
│   │   └── Assets/
│   └── Output/
│       ├── Screenshot from 2026-05-10 00-33-32.png
│       ├── Screenshot from 2026-05-10 00-34-02.png
│       ├── Screenshot from 2026-05-10 00-39-02.png
│       ├── Screenshot from 2026-05-10 00-43-10.png
│       └── Screenshot from 2026-05-10 00-50-00.png
└── Flappy Bird Game/
    ├── Code Files/
    │   ├── Main.cpp
    │   ├── Bird.h
    │   ├── Pipe.h
    │   ├── HighScore.txt
    │   ├── a.out
    │   └── Assets/
    └── Output Files/
        ├── Screenshot from 2026-05-10 00-44-52.png
        ├── Screenshot from 2026-05-10 00-45-37.png
        ├── Screenshot from 2026-05-10 00-45-58.png
        ├── Screenshot from 2026-05-10 00-47-17.png
        ├── Screenshot from 2026-05-10 00-48-10.png
        └── Screenshot from 2026-05-10 01-00-53.png
```

## Requirements

- **C++ Compiler** (GCC, Clang, or MSVC)
- **SFML Library** (Simple and Fast Multimedia Library)
- **Linux/Unix or Windows/macOS with compatible toolchain**

## Building and Running

Each game can be compiled individually:

```bash
# Navigate to game directory
cd "Timber Game"
g++ -c Timber.cpp -o Timber.o
g++ Timber.o -o timber_game -lsfml-graphics -lsfml-window -lsfml-system -lsfml-audio
./timber_game
```

Alternatively, run the pre-compiled executables:
```bash
./a.out  # in the respective game directory
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Features Overview

| Game | Type | Players | Difficulty | Key Features |
|------|------|---------|------------|--------------|
| Timber Man | Action/Reflex | 1 | Progressive | Obstacle dodging, scoring |
| Pong | Arcade | 2 | Adjustable | Classic gameplay, ball physics |
| Zombie Arena | Shooter | 1 | Wave-based | Combat, power-ups, AI enemies |
| Car Dodging | Action | 1 | Progressive | Vehicle control, collision detection |
| Flappy Bird | Casual | 1 | Consistent | Obstacle navigation, high scores |

## Technologies Used

- **Graphics**: SFML Graphics Module
- **Audio**: SFML Audio Module
- **Input Handling**: SFML Window Module
- **Object-Oriented Design**: Classes and inheritance
- **File I/O**: High score persistence

## Contributing

Feel free to fork this repository and submit improvements or bug fixes via pull requests.

## Author

Created by [@Always-Amulya7](https://github.com/Always-Amulya7)
LinkedIn [Amulya Shrivastava](https://www.linkedin.com/in/amulya-shrivastava-11a0a9288/)

---

Enjoy the games! 🎮
