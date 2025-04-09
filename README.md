# EyeBlink-Dino-Control

This project is a Dino game controlled by eye blinks, using OpenCV, MediaPipe, and CVZone for eye blink detection. The game includes various obstacles and sound effects.

## Features
- **Eye Blink Detection**: Control the Dino character by blinking your eyes
- **Obstacles**: Includes cacti and pterodactyls as obstacles
- **Sound Effects**: Jump, points, and game over sound effects enhance the gaming experience
- **Animations**: Smooth animations for Dino running, jumping, and ducking

## Requirements
- Python 3.6+
- OpenCV
- cvzone
- MediaPipe
- PyAutoGUI
- Pygame

## How to Play
- **Jump**: Blink your eyes to make the Dino jump
- **Duck**: Press the down arrow key to make the Dino duck
- **Restart**: Press the space bar or the up arrow key to restart the game after a game over

## Game Controls
- **Blinks**: Control the Dino's jump
- **Arrow Keys**: Additional controls for ducking and jumping

## Code Overview
- **Eye Blink Detection**: Uses OpenCV and MediaPipe to detect blinks and control the Dino's jumps
- **Game Mechanics**: Implemented with Pygame for animations, obstacle spawning, and collision detection
- **Sound Effects**: Added using Pygame mixer for enhanced user experience

## Acknowledgements
- Inspired by the Chrome Dino game
- Uses OpenCV, MediaPipe, CVZone, PyAutoGUI, and Pygame for various functionalities
