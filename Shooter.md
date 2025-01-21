# Asteroid Game

## Table of Contents

- [Introduction](#introduction)
- [Game Features](#game-features)
  - [Main Screens](#main-screens)
  - [Game Mechanics](#game-mechanics)
  - [Asteroid Types](#asteroid-types)
  - [Game Progression](#game-progression)
  - [Collision and Lives](#collision-and-lives)
  - [Pause and Resume Functionality](#pause-and-resume-functionality)
  - [Game Over Screen](#game-over-screen)
- [Audio](#audio)
- [How to Run the Game](#how-to-run-the-game)
- [Additional Features](#additional-features)

## Introduction

This is an asteroid-themed space shooter game where players navigate a spaceship through space, dodging and shooting down different types of asteroids. The goal is to score as high as possible while avoiding collisions with asteroids and enemy bullets. The game progressively becomes more challenging as the player's score and levels increase.

## Game Features

### Main Screens

The game consists of two primary screens:

1. **Start Screen**:
   - Contains buttons for `Start` and `High Score`.
   - Clicking `Start` begins the game.
   - Clicking `High Score` displays the highest score achieved in the game.

2. **High Score Screen**:
   - Displays the current high score.

### Game Mechanics

- **Controls**:
  - `A` for moving left.
  - `D` for moving right.
  - `Space` for firing bullets.
- The spaceship starts at the bottom center of the screen.
- As the player progresses, their score, level, and lives are shown on the top right of the screen.
- Each level starts with Level 1, and as the score increases, the level also increases.

### Asteroid Types

There are three distinct types of asteroids:

1. **Type 1**: Destroyed with 1 bullet.
2. **Type 2**: Destroyed with 3 bullets.
3. **Type 3**: Destroyed with 5 bullets.
   - The asteroid flashes as it gets hit by bullets.

### Game Progression

- As the player advances past Level 6, a new category of asteroids is introduced:
  - This asteroid fires bullets in 6 directions and takes 7 bullets to be destroyed.
- With each level increase:
  - The number of asteroids on the screen increases.
  - The speed of falling asteroids also increases.

### Collision and Lives

- When the spaceship collides with an asteroid, the player loses a life.
- The player's remaining lives are displayed on the top right of the screen.
- Upon collision, the spaceship relocates to the bottom center of the screen.

### Pause and Resume Functionality

- Pressing `Esc` pauses the game.
- The pause menu contains three buttons:
  - `Resume`: Continues the game.
  - `Start Again`: Resets the game to Level 1.
  - `Main Menu`: Returns to the Start Screen.

### Game Over Screen

- Upon losing all lives, the game transitions to a **Game Over** screen.
- This screen shows:
  - The player's high score.
  - The current score.
  - Buttons to either go back to the Main Menu or Start Again (resetting to Level 1).

## Audio

- **Button Clicks**: Each button press has an accompanying click sound.
- **Collision Sounds**:
  - Spaceship colliding with an asteroid triggers a sound effect.
  - Asteroid destruction has a unique sound.
- **Background Music**:
  - Constant background music plays during the game mode.
  - Different background music is played on the Start Screen and Game Over Screen.

## How to Run the Game

1. Download the game files from the repository.
2. Extract the files and navigate to the project folder.
3. Open the terminal/command prompt in the project directory.
4. Run the game executable (or open the game project in the development environment and execute).
5. Use the following controls:
   - `A` and `D` to move left and right.
   - `Space` to fire bullets.
   - `Esc` to pause the game.

## Additional Features

- **Increasing Difficulty**: More challenging asteroid types and increasing asteroid speed as the level progresses.
- **Enhanced Asteroid Interaction**: Asteroids flashes when hit, and new types of asteroids appear at higher levels with unique behaviors.
- **Multiple Audio Effects**: Immersive audio with distinct sound effects for different actions and screens.