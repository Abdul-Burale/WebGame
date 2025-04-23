# 🕹️ 2D Platformer Game

A smooth and stylish pixel-art 2D platformer built with Python and Pygame. Dash, jump, and shoot your way through multiple handcrafted levels filled with enemies, effects, and atmospheric environments.

---

## 🎮 Features

- Classic platformer movement: run, jump, wall-slide, and dash!
- Dynamic enemies that patrol and shoot projectiles
- Particle effects (leaves, sparks, dashing trails)
- Screenshake and transition animations for added juice
- Multi-level progression with JSON-based tilemaps
- Layered rendering: background, silhouettes, and dynamic elements
- Retro-style graphics and sound effects

---

## 🛠️ Installation

### Requirements

- Python 3.8+
- Pygame

Install dependencies with:

```bash
pip install pygame
Controls

Key	Action
A	Move Left
D	Move Right
Space	Jump
X	Dash
ESC	Quit Game
Code Structure
Game.py - Core game loop and asset management

scripts/entities.py - Player and enemy behavior

scripts/tilemap.py - Tile-based level loading and collision

scripts/particle.py - Particle effect system

scripts/spark.py - Spark effects for collisions

scripts/clouds.py - Background cloud parallax

scripts/utils.py - Helper functions and animation loader

Credits
Built using Pygame.
Assets and sound effects are placeholders or original—feel free to replace them with your own!
