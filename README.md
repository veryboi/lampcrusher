# Lamp Crusher: A Pixar-Inspired Interactive Game

## Project Overview

Lamp Crusher is an exciting 3D interactive game inspired by the iconic Pixar lamp character. In this game, players control the lamp and must crush falling letters before the sun's light fades away. The game combines engaging gameplay with advanced graphics techniques to create an immersive and visually stunning experience.

## Team Members

- Zifan Zhou (zzhou25@g.ucla.edu)
- Patrick Li (patrickli@g.ucla.edu)
- Brandon Shihabi (brandonshihabi@g.ucla.edu)

## Game Concept

Players take on the role of the Pixar lamp in a stylized 3D environment. The objective is to crush falling letters to gain health and score points before the sun's light (represented by the player's health) completely fades away, leaving the lamp as the only remaining light source.

## Key Features

- **Dynamic Lighting**: The lamp serves as a moving light source, creating realistic shadows and atmospheric effects.
- **Interactive Gameplay**: Control the lamp's movement (WASD keys) and jumping (spacebar) to crush letters and score points.
- **Camera Control**: Use the mouse to look around and survey the game environment.
- **Health System**: Player's health is represented by the brightness of the sun, which gradually dims over time.
- **Scoring**: Earn points by successfully crushing letters.

## Advanced Technical Features

1. **Shadow Mapping**: Realistic shadow rendering using PCF filtering for soft shadow edges.
2. **Collision Detection**: Oriented Bounding Box (OBB) collision detection for precise interactions between the lamp and letters.
3. **Temporal Anti-Aliasing**: Smooth, anti-aliased visuals using temporal data from previous frames.
4. **Physically Based Lighting**: Utilizes Cook-Torrance specular model and Lambertian diffuse shading for realistic lighting calculations.

## Implementation Details

- **Lighting**: Two light sources - the lamp and a directional "sun" light.
- **Object Transforms**: Matrices and linear algebra for smooth object movements.
- **Graphics Techniques**: Dynamic lighting, shading, and advanced rendering methods for a visually appealing experience.

## Getting Started

(Include instructions for setting up the project, dependencies, and how to run the game)

## Controls

- **WASD**: Move the lamp
- **Spacebar**: Jump
- **Mouse**: Control camera view


## Acknowledgments

- Inspired by the Pixar lamp character
- Developed as part of CS174A at UCLA
