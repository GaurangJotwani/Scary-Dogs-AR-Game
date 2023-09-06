# Scary Dogs AR Game

Welcome to Scary Dogs, a simple spatial AR game created using Unity and Wikitude. The game involves the player being chased by dogs, with the objective of avoiding them for as long as possible. The game gets progressively harder as time goes on, with the dogs getting faster every 30 seconds.

## Getting Started

If you have already cloned or downloaded this project, you can skip this step. Otherwise, follow these instructions:

1. Clone or download the repository.
2. Open the project in Unity.
3. Open the "Scenes" folder and open the "Scary Dogs" scene.
4. Build and run the project on your mobile device.

## Game Rules

* At startup, three dogs are spawned that chase the player.
* The UI updates to show how many dogs have touched the player. When a dog touches the player, it disappears.
* The UI also shows a timer for how long the player has been alive.
* Every 30 seconds, the dogs' speed increases.
* The game is reset when the player is touched by all three dogs.
* The timer resets to 0:00 and three new dogs are randomly placed.

## Resources

In order to set up the game properly, make sure that the AR camera has a collider, a rigid body with gravity off, and a trigger. The dog also needs a collider and a trigger. More information on setting up colliders and triggers can be found here:

https://learn.unity.com/tutorial/physics-interactions-colliders-and-triggers-2019-3

## Screenshots

Screenshots of the game can be found in the `Screenshots` folder.

## Bonus

The project already includes a Canvas UI to allow the user to reset the game using Canvas UI Tutorials.

Thanks for playing Scary Dogs!
