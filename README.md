# Raylib RPG Example

An example RPG Game.

Demo Gamplay
https://youtu.be/9apXiHKIlsg

## Design Document
https://docs.google.com/document/d/1lxpR6WbbjmCi9X_seGPYPYz7UhFcAKkX5Xl3pVfEwHs/edit?usp=sharing

## Video Overview
https://youtu.be/krykjMt9ZKQ

# Building
The RPG Example uses premake just like all other items in raylib extras. A tutorial on how to build a raylib project with premake can be found here. https://github.com/raylib-extras/game-premake

This example includes the visual studio projects and windows makefiles that were created by premake, but other build systems can be used (like make files for linux) by running premake5 for the desired platform.
The premake system will automatically download raylib for you.

# State
The current example is feature complete and would be considered in 'beta' state. It has all the main features that are required by the game.

# Features
This sample has examples of how to do the following things in raylib

- Game State
- Menus
- Quiting the game from menus
- Pause/Resume Game
- Tile Map with object layers
- Click to Move
- 2D Camera that keeps the player in view
- Simple Effects
- Basic AI
- Background Music
- Sound Effects
- Resource Loading

# C++
This example does use C++. The use of C++ has been keept at a resonable level. C++ is used for

- Containers (vector, list, map, etc...)
- Simple classes
- Menu Screens

Every use of C++ in this project can be replicated in C, or any other language. The main reason for using C++ was to not clutter up the project with implementations of common containers such as linked lists.
Do not fear the C++. C++ is just another tool to use to solve problems.
