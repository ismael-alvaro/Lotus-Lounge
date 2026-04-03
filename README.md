# Lotus Lounge

## Overview

**Lotus Lounge** is a 2D game project developed in **C** using the **Raylib** library. The project is structured in a modular way, separating game logic, player behavior, menu handling, and game phases into different source files. The focus of the project is on practicing low-level game development concepts such as rendering, input handling, audio management, and basic game state control.

<img width="1280" height="720" alt="play" src="https://github.com/user-attachments/assets/c8aecb19-8f86-401c-9775-b741e3ae4c28" />

---

## Project Linearity

The project follows a clear and linear execution flow, typical of games developed in C with Raylib:

1. **Program Entry**

   * The execution starts in `main.c`.
   * Window creation, audio initialization, and the main game loop are defined here.

2. **Menu System**

   * Implemented in `menu.c`.
   * Responsible for drawing the main menu, handling user input, and controlling transitions between menu states and the game.

3. **Game Loop and Core Logic**

   * Managed by `game.c` and `game.h`.
   * Controls the current game state, updates entities, and handles rendering during gameplay.

4. **Player Logic**

   * Implemented in `player.c`.
   * Handles player movement, animations, collisions, and interactions with the environment.

5. **Game Phases**

   * The first phase is implemented in `phaseOne.c`.
   * Defines level-specific logic, obstacles, enemies, and progression rules.

6. **Assets and Resources**

   * Audio and image assets are stored in the `assets/` directory.
   * Game resources are loaded during runtime and used by the corresponding systems.

7. **Build Process**

   * The project is compiled using a `Makefile`, which links Raylib and builds the executable.

---

## Project Structure

```
Lotus_Lounge/
├── assets/        # Images and audio files
├── data/          # Auxiliary project notes
├── saves/         # Save-related placeholders
├── utils/         # Utility placeholders
├── main.c         # Program entry point
├── menu.c         # Menu logic
├── game.c / game.h# Core game logic and states
├── player.c       # Player behavior and mechanics
├── phaseOne.c     # First game phase implementation
├── Makefile       # Build configuration
└── raylib.h       # Raylib header
```

---

## Tools and Technologies Used

* **C Language**
* **Raylib** – graphics, input, audio, and window management
* **Makefile** – build automation
* **VS Code** – development environment configuration

---

## Conclusions

* The project demonstrates a clear separation of concerns, even when using a low-level language such as C.
* Modularization improves readability and maintainability of the codebase.
* Raylib provides a simple and effective framework for learning 2D game development.
* The structure allows future expansion, such as adding new phases, enemies, or gameplay mechanics.

---

## Notes

This project emphasizes learning and experimentation with game development fundamentals, focusing on structure, clarity, and control over the execution flow rather than complex engines or abstractions.


### Executors:
André Lima - alj  
Lucas Leal - lfla2  
Maria Gabriella - mgma  
Ismael Álvaro - ials  
Matheus Braglia - mbcv  
Maria Gabriella - mgma  
Milla Rwana - mras3  
Rayssa Vitória - rvls2  
