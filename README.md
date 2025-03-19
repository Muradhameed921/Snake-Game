# Snake Game - Assembly Language Project

## Introduction
This project is a Snake Game developed in Assembly Language as part of the Computer Organization and Assembly Language (COAL) course. The game utilizes fundamental assembly language concepts such as instruction set architecture, memory addressing, branching, bit manipulation, stack operations, subroutines, string operations, and interrupts.

## Features
- **Introductory Display:** Displays the name of the game and the roll numbers of both developers.
- **Game Menu:** Provides key bindings for controlling the snake.
- **Game Screen:** Fully functional game logic including movement, food collection, and collision detection.
- **Score Display:** Keeps track of the player's score as they collect food.
- **Game Over Display:** Shows a message when the game ends due to collision.

## How to Play
1. Run the ASM file using an x86 emulator like DOSBox or an assembler like MASM/TASM.
2. Use the provided keys to move the snake in different directions.
3. Collect food to increase the score.
4. Avoid colliding with the walls or yourself, or the game will end.
5. The game displays "Game Over" when the player loses.

## Controls
- **Arrow Keys:** Move the snake in the respective direction (Up, Down, Left, Right)
- **ESC Key:** Exit the game

## Requirements
- MASM/TASM or an equivalent assembler for running x86 Assembly programs.
- DOSBox (if running on a modern system) for executing 16-bit assembly code.

## Installation & Execution
1. Install DOSBox and MASM/TASM.
2. Place the ASM file in the appropriate directory.
3. Open DOSBox and navigate to the directory where the file is stored.
4. Assemble and run the file using:
   ```bash
   masm Program1_Coal.asm;
   link Program1_Coal.obj;
   Program1_Coal.exe
   ```

