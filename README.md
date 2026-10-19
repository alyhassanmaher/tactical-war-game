# Tactical War Game

Two-player, turn-based strategy game built with Pygame for the Python Programming course at ESLSCA University.

## Gameplay
Each player commands four units on a grid battlefield. The first player to eliminate the enemy army wins.

| Unit | Strength |
|---|---|
| Infantry | Balanced, high HP |
| Archer | Long attack range, fragile |
| Cavalry | Fast movement, high HP |
| Tank | Heaviest armour, highest HP and attack |

- Randomly generated terrain with obstacles
- Two moves per turn
- Health bars, move and attack highlights, and unit selection
- Main menu, game and game-over screens

## Controls
| Action | Input |
|---|---|
| Select, move, attack | Left click |
| End turn | END TURN button |
| Start or restart | Space |
| Quit | Esc |

## Run
```bash
pip install -r requirements.txt
python tactical_war_game.py
```
