# Stick Hero Game (Jack / Nand2Tetris)

## Project Overview
**Stick Hero** is an arcade-style platform game built entirely in the **Jack programming language** as part of the Nand2Tetris course.  
Players extend a stick to cross gaps between platforms, earning points for successful crossings and bonus points for perfect landings. The game features smooth stick animations, camera scrolling, real-time score tracking, and progressive difficulty.

This project demonstrates object-oriented programming, state machines, and game mechanics, and it runs both on the **VM Emulator** and on a **Raspberry Pi 4B** for a custom console setup.

---

## Features
- Dynamic stick growth and rotation mechanics  
- Smooth camera scrolling and platform rendering  
- Real-time score tracking and high score saving  
- Progressive difficulty every 5 points  
- Full game state machine: Title, Stick Growing, Rotating, Hero Moving, Game Over  
- Raspberry Pi integration for custom console gameplay  

---

## Implementation / How to Run

### 1. On VM Emulator
1. Compile all Jack files:
```bash
./JackCompiler.sh
Open the VM Emulator:

bash
Copy code
./VMEmulator.sh
Load the compiled .vm files.

Set Animation Speed → Fast for smooth gameplay.

Press any key to start the game.

2. On Raspberry Pi 4B
Copy the project folder to your Raspberry Pi.

Install required dependencies if necessary (e.g., VM Emulator on Raspberry Pi).

Compile the Jack files using JackCompiler.sh.

Run the VM Emulator to start the game.

Optionally, connect external buttons to control game inputs on the custom console.

Repository Structure
mathematica
Copy code
StickHero/
├── Main.jack
├── Game.jack
├── Stick.jack
├── Platform.jack
├── Score.jack
├── Random.jack
├── Constants.jack
├── .gitignore
├── LICENSE
└── README.md
License
This project is licensed under the MIT License. See LICENSE file for details.

Author
Manideep — B.Tech CSE (AI), Amrita Vishwa Vidyapeetham, Bengaluru.
Passionate about system-level design, game development, and embedded systems.

yaml
Copy code
