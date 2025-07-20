# Tresure-Hunt

# Treasure Race

A competitive treasure-hunting game where you race against a strategic AI opponent to be the first to reach 100 points!

## Game Overview

Treasure Race is a turn-based strategy game played on a grid. You and the AI compete to collect treasures (+5, +10, +15 points) while avoiding traps (–10 points). 
The first to reach 100 points wins!

## Features

-  **Smart AI**: Uses A* pathfinding and strategic freezing
-  **Strategic Gameplay**: Treasures, traps, freezing, and collisions
-  **Freeze Ability**: Temporarily block your opponent for 5 turns
-  **Dynamic Board**: Treasures and traps spawn automatically
-  **Visual Feedback**: Icons, progress bars, and clear score indicators

## How to Play

- **Move** – Arrow keys  
- **Freeze** – F key (once per 5 turns)  
- **Pause** – Space bar  
- **Goal** – Reach 100 points before the AI by collecting treasures and avoiding traps

## Installation

```bash
pip install -r requirements.txt
python main.py
