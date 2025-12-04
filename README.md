# A Fox'sQuest
A Fox’s Quest is a small 2D adventure platformer developed in Python using Pygame. This project was built and tested in Visual Studio Code, and although simple in scope, it showcases a functional game loop, character interactions, enemies, collectibles, and level logic.

Project Structur:
The game is divided into several folders and files:
clases/foxy.py – Contains the player class Foxy and all player-related logic.
clases/animals.py – Contains enemy classes (Rabbit, Deer, Bear) and their behaviors.
items/ folder
timer.py – Handles the level timer.
assets.py – Stores items such as berries, picnic baskets, platforms, and the level goal.
settings.py – Defines global settings used across the entire game (screen size, colors, FPS, etc.).
game.py – The core “juggernaut” file that manages the game loop, game states, collisions, drawing, events, and overall logic.
main.py – The launcher file. Simply press “Start Debugging” in VS Code to run the game.

Running the Game:
Open the project in Visual Studio Code.
Ensure Python and Pygame are installed.
Run main.py using the VS Code debugger or a terminal

Controls:
Move Left: ← or A
Move Right: → or D
Jump: W, ↑, or J
Attack: Spacebar
Pause Game: P
Open Controls Menu: H

Project issues:
This project was created by a single developer (me) under significant time constraints. As a result, several known limitations exist:
Levels are not dynamic — they do not generate random layouts, and the structure remains the same on each playthrough.

Link to github:https://github.com/JeremyCordero/A-Fox-s-Quest
Difficulty remains mostly static, as new enemy patterns or extended platform sections were not implemented.
Animations are limited, and some visual effects could not be completed.
Expanding level variety or adding procedural generation was not possible during development.
Despite these limitations, the game runs smoothly and offers a simple and enjoyable experience.


Return to Main Menu / Exit Level: ESC
