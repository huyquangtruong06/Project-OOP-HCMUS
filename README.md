Tower Defense Game
Object-Oriented Programming Project
Language: C++
University: Ho Chi Minh City University of Science
Lecturer: TRƯƠNG TOÀN THỊNH

1. Introduction
This project aims to apply foundational programming techniques, data structures, and object-oriented programming (OOP) principles to build a basic Tower Defense game using the C++ language.

To successfully develop this game, students should have knowledge of:

File I/O operations

Program control flow

Basic data structures

Object-oriented programming

This project serves as a tutorial for students to practice game development at an introductory level. It also encourages independent research and teamwork to enhance the final product.

2. Game Scenario
At the start of the game, a map and a parameter configuration table will appear for players to input desired values.

Once the setup is complete, the game runs automatically, and players observe the outcome.

The game ends under one of the following conditions:

All enemies are destroyed.

An enemy successfully reaches the finish line.

After the game ends, the player is prompted:

Press 'y' to restart the game with the original state.

Press any other key to exit the game.

If the player defeats all enemies, they proceed to the next level. Each new level increases difficulty (e.g., more enemies, tougher resistance, etc.).

The game concludes when the player reaches a predefined final level (win condition) or restarts after game over.

3. Project Requirements
The following key features must be implemented:

🔫 Collision Handling
Implement bullet-enemy collision detection.

Design visual effects for collisions to make the gameplay more engaging.

💾 Save/Load System
Allow players to save the game at any time.

Provide an option to load previously saved games to continue from where they left off.

🗺 Game Setup Interface
Instead of starting the game immediately, display the map, buildable tower locations, and enemy paths before gameplay begins.

Allow players to analyze the environment and choose suitable parameters for better strategy planning.

🧩 Multi-Level Design
The game must include at least 4 levels, each with a unique map.

Increasing difficulty may involve faster enemies or higher enemy count.

📜 Game Menu
Design a game menu system with options such as:

New Game

Load Game

Settings

Implement two types of audio:

Background music

In-game sound effects

Include on/off toggles for both sound types.

🌟 Special Feature (Team-Specific)
Each team must develop a unique advanced feature that distinguishes their game.

This special feature must not be shared among different teams.
