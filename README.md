# Space Survival 🚀

A classic console-based space shooter game developed in C++ where players navigate through space, avoiding obstacles and shooting enemies to survive.

## 🎮 Game Overview

**Space Survival** is an exciting arcade-style shooter game that runs directly in your console/terminal. Take control of a spaceship, dodge incoming obstacles, and use your weapons to blast through enemies while trying to achieve the highest score possible!

## 👥 Development Team

**Project Group 11:**
- **Ashan** (IM/2022/025)
- **Nirasha** (IM/2022/024) 
- **Tharindu** (IM/2022/112)
- **Gihan** (IM/2022/111)

## ✨ Features

### 🎯 Game Modes
- **Campaign Mode**: Start with 5 ship lives - each collision reduces your strength by 1
- **Time-Based Mode**: Race against time with limited energy to achieve maximum score

### 🎮 Gameplay Elements
- Smooth ship movement controls
- Dual bullet shooting system
- Dynamic obstacle generation
- Collision detection system
- High score tracking and saving
- Sound effects for enhanced experience
- ASCII art graphics and animations

### 🎨 Visual Features
- Colorful console interface
- Custom ASCII art ship design
- Animated game over screen
- Multiple themed UI screens
- Border graphics and visual effects

## 🎮 Controls

| Key | Action |
|-----|--------|
| `←` | Move ship left |
| `→` | Move ship right |
| `Space` | Fire bullets |
| `Esc` | Pause/Exit game |

## 🚀 Getting Started

### Prerequisites
- Windows operating system (uses Windows-specific libraries)
- C++ compiler (Visual Studio, Dev-C++, or similar)
- Console/Command Prompt support

### Installation & Running

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/space-survival.git
   cd space-survival
   ```

2. **Compile the game:**
   ```bash
   g++ -o space_survival "space survival.cpp"
   ```

3. **Run the game:**
   ```bash
   ./space_survival.exe
   ```

## 📁 Project Structure

```
space-survival/
│
├── space survival.cpp    # Main game source code
├── highscore.txt        # High score storage (auto-generated)
├── README.md           # This file
└── docs/               # Documentation (if any)
```

## 🎯 How to Play

1. **Start the Game**: Press `Space` on the main menu to start your rocket engine
2. **Enter Your Name**: Provide your astronaut name for the leaderboard
3. **Choose Game Mode**: Select between Campaign or Time-based mode
4. **Survive & Score**: 
   - Use arrow keys to move your ship
   - Press `Space` to shoot bullets at incoming obstacles
   - Avoid collisions to maintain your ship's health
   - Achieve the highest score possible!

### Campaign Mode
- Start with 5 ship lives
- Each collision reduces your strength
- Game ends when all lives are lost
- Focus on survival and steady scoring

### Time-Based Mode
- Limited energy/time to play
- Race against the countdown timer
- Maximize your score before energy runs out
- High-intensity gameplay

## 🏆 Scoring System

- **Successful Hit**: +1 point per obstacle destroyed
- **High Score**: Automatically saved and displayed
- **New Record**: Special congratulations message for beating previous high scores

## 🔧 Technical Details

### Dependencies
- `<iostream>` - Input/output operations
- `<windows.h>` - Windows console handling and sound
- `<conio.h>` - Keyboard input detection
- `<time.h>` - Random number generation
- `<fstream>` - File handling for high scores

### Key Functions
- **Movement System**: Smooth ship controls with boundary detection
- **Bullet System**: Dual-bullet firing mechanism
- **Collision Detection**: Precise hit detection between objects
- **Score Management**: File-based high score persistence
- **Sound Effects**: Beep sounds for game events

## 🎨 Game Elements

### Ship Design
```
   *
[]*[]
=***=
```

### Obstacle Pattern
```
 -^-
 ***
-!!!-
  +
```

## 🐛 Known Issues & Limitations

- **Platform Dependency**: Currently Windows-only due to `windows.h` usage
- **Console Colors**: May not display correctly on all terminal types
- **Fixed Resolution**: Designed for standard console window sizes

## 🚧 Future Enhancements

- [ ] Cross-platform compatibility (Linux/Mac support)
- [ ] Multiple difficulty levels
- [ ] Power-ups and special weapons
- [ ] Multiplayer support
- [ ] Enhanced graphics and animations
- [ ] Sound track and improved audio
- [ ] Level progression system

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

### How to Contribute
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📞 Support & Contact

If you encounter any issues or have questions about the game, please:
- Open an issue on GitHub
- Contact the development team members

---

**Enjoy your space survival adventure! 🚀✨**

*Made with ❤️ by Project Group 11*
