# Asteroid Game

Arcade game project in Python using Pygame, inspired by Asteroids.

## About

This project implements a player-controlled spaceship in a space field with dynamically spawned asteroids. The game is built around Pygame sprite classes and groups to organize updates, rendering, collisions, and object spawning.

At the current stage, the game includes:

- ship movement with rotation and directional movement
- projectile shooting
- continuous asteroid spawning
- collisions between the ship and asteroids
- collisions between shots and asteroids
- an object-oriented structure with `Player`, `Asteroid`, `Shot`, and `AsteroidField`

## Technologies

- Python 3.13+
- Pygame 2.6.1

## How to Run

If you use `uv`:

```bash
uv run main.py
```

If you prefer the local virtual environment:

```bash
.venv/bin/python main.py
```

## Controls

- `A`: rotate left
- `D`: rotate right
- `W`: move forward
- `S`: move backward
- `Space`: shoot

## Project Structure

- `main.py`: main game loop
- `player.py`: spaceship logic
- `asteroid.py`: asteroid behavior
- `asteroidfield.py`: asteroid spawning logic
- `shot.py`: bullets fired by the ship
- `circleshape.py`: base class for circular entities
- `constants.py`: game constants
- `logger.py`: state and event logging

## Goal

The goal of this project is to serve as a simple incremental implementation of a 2D game using Python and Pygame, covering concepts such as:

- game loop
- delta time (`dt`)
- sprites and groups
- vectors with `pygame.Vector2`
- entity collision
- class-based game logic
