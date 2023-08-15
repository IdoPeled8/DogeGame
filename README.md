# Doge Game
The Doge Game is a simple UWP (Universal Windows Platform) game developed using C# and XAML. The game features a player-controlled character (represented by an image of a doge) that can move in four directions using the arrow keys. The objective is to avoid the enemy characters (represented by images of enemies) that move towards the player. If the player character touches an enemy, the player loses, and if all enemies are eliminated, the player wins.

# Gameplay Mechanics
The player character can move up, down, left, and right using the arrow keys.

Enemies move towards the player character using calculated angles.

Collision detection ensures that enemies touching the player character result in a game over.

The player can start, stop, resume, and exit the game using keyboard shortcuts or buttons.

# Classes
The game consists of several classes:

MainPage: The main page of the UWP app, handling UI elements and interactions.

GameManager: Manages the game mechanics, such as updating entity positions, collision detection, and game win/loss conditions.

Entity: The base class for player and enemy entities, containing common properties and methods.

Player: Extends Entity, representing the player character and handling player movement.

Enemy: Extends Entity, representing the enemy characters and handling their movement towards the player.

Movements: Manages player movement using key presses and releases.

# Features
Player movement using arrow keys.

Dynamic enemy movement towards the player.

Collision detection for enemies and player character.

Game win/loss conditions and corresponding messages.

Keyboard shortcuts for game controls.

Saving and loading game state.

#Getting Started
Clone the repository.

Open the project in Visual Studio.

Build and run the UWP app.

Use arrow keys to control the player character and avoid enemies.

Use keyboard shortcuts or buttons to start, stop, resume, or exit the game.

Enjoy the simple gameplay and challenge!

Feel free to explore the code, make modifications, and enhance the game according to your preferences.

