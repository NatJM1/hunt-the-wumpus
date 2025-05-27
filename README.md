readme_content = """# Hunt the Wumpus

A Python-based reimagining of the classic Hunt the Wumpus game using pygame.

## Overview
This game is a graphical version of the 1970s text-based adventure, where players navigate a dangerous cave filled with hazards—including bottomless pits, bats that relocate you randomly, and the dreaded Wumpus itself.

Your goal? Survive the cave and take down the Wumpus before it gets you.

## Gameplay Features
- Exploration: Move through interconnected rooms in a mysterious cave.
- Hazards: Avoid pits and bats that disrupt your movement.
- Hunting: Carefully aim and shoot arrows to eliminate the Wumpus.
- Randomization: The cave layout, hazards, and Wumpus location change every game.

## Controls
- Arrow keys: Move through the cave.
- Shift + Arrow key: Fire an arrow in the chosen direction.
- Escape: Quit the game.
- Mouse Click:
  - Click Restart to start fresh.
  - Click Quit to exit.

## Installation & Running the Game
### Prerequisites
- Python 3.x
- pygame installed (pip install pygame)

### Running the Game
1. Clone this repository:
   git clone https://github.com/NatJM1/hunt-the-wumpus.git
   cd hunt-the-wumpus

2. Run the game:
   python main.py

## Winning & Losing
- Victory: Successfully shoot the Wumpus before it gets you.
- Defeat: Fall into a pit, get eaten by the Wumpus, or run out of arrows.

## Author
Created by NatJM1. Feel free to contribute or suggest improvements!
"""

# Optional: Save to README.md file
with open("README.md", "w") as f:
    f.write(readme_content)
