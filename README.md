# Hermit
A man. A horse. A nature.

(Winner of Fall 2015 CS 15-112 Term Project Contest at CMU)

## DEPENDENCIES
* Python 3 (https://www.python.org/downloads/)
* Poetry (`python3 -m pip install poetry`)

## HOW TO RUN

Download the project. In terminal, type:
1. Create a virtual environment and enter it: `poetry shell`
2. Download Dependencies: `poetry install`
3. Run: `python src/main.py`

## VIDEO
https://www.youtube.com/watch?v=mPYeTJd8klQ

## Features
* EVERYTHING Procedurally generated
* Day-night transition
* Extremely detailed animations

## CONTROLS
* Right arrow: Walk
* Left arrow: Draw bow
* Up arrow: Mount & dismount
* Down arrow: Drink
* Slash(/): Bring up console

## CONSOLE COMMANDS
* `set time -t`: set the current time to t (t>0)
* `set speed -s`: set player walking speed to s (s>0)
* `set terrain -n`: set the current terrain to n (n=0,1)
* `set tree density -n`: set the density of trees to n trees per two screens (n>0)
* `spawn -x -n`: spawn number n of animals x (x=deer,crane,bird,...,n>0)
* `fullscreen -b`: toggle fullscreen (optional parameter b=0,1)
* `restart`: restart the program
