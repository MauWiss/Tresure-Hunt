
# Treasure Race

A competitive treasure-hunting game where you race against a strategic AI opponent to be the first to reach 100 points!

##  Demo Videos 
- **Presentation Video:** [YouTube Link](https://youtu.be/EBFKXpef6Vw)
- **Game Explanation:** [YouTube Link](https://www.youtube.com/watch?v=heuuk2oSoVI)

##  Project Documentation 

- **Full Project Report (SRS):** [Google Docs Link](https://docs.google.com/document/d/1ei_D8Pw3341YN6k0aRl-e-VyGRl45jF3QJSDUIYSNCc/edit?tab=t.0)
- **Project Presentation:** [Canva Link](https://www.canva.com/design/DAGtdb62nBo/KauVAMfmx_25QJTd280FnA/edit?utm_content=DAGtdb62nBo&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)

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
