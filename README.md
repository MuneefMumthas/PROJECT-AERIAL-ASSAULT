# Game Description
**Game Name:** Aerial Assault

A 2D space shooter game created using Windows Forms Application (C#) in Visual Studio. The game's objective is to shoot as many enemy spaceships as possible. At the beginning of the game, the player has full health and ammo. Enemy spaceships are randomly spawned above the player spaceship and move downward. When the player spaceship collides with an enemy spaceship, the player spaceship's health decreases and the enemy spaceship is eliminated. Each time the player shoots an enemy spaceship, the score increases. When the score reaches 10, both the enemy and player spaceship speeds are increased. The speed is further increased upon reaching a score of 20 and 30, then the speed stays the same. When ammo count reaches 0, an ammo crate is randomly spawned near the player to collect. If one of the enemy spaceships goes below the player, the game will end. Similarly, the game will also end, if the player's health reaches 0.
      
## Features

1. The game has a menu which can be navigated solely using keyboard controls.

2. The player can move left and right by pressing the left and right arrow keys. 
3. The player can shoot bullets/rockets by pressing the SPACE key.
4. At the start, the player begins with 100 health, 10 ammo, and a score of 0.
5. Enemy spaceships spawn randomly across the screen and move downward.
6. If an enemy spaceship collides with the player spaceship, the player's health decreases, and the enemy spaceship is eliminated.
7. When the player shoots a bullet/rocket, the ammo count decreases by 1.
8. The score increases by 1 whenever an enemy spaceship gets eliminated by a bullet/rocket.
9. The game has 3 levels, as the player scores 10, 20, and 30 points, the speed of both enemy and player spaceships are increased
10. An ammo crate is spawned randomly across the map when the ammo count hits 0.
11. When the player collects the ammo crate, they are granted 5 ammos.
12. When the player's health reaches 0, the game will be over.
13. If an enemy spaceship passes below the player's spaceship, the game will be over.
14. The game includes background music and sound effects for kills and collecting ammo crates.

# Game Analysis & Design

## Game Use Case Diagram 

![PR1 Use Case Diagram](https://github.com/MuneefMumthas/CO452-Muneef-22206529/blob/main/PR1Game/Images%20for%20PR1/Muneef-PR1-UseCaseDiagram.jpg)

## Game Class Diagram
 
![PR1 Class Diagram 1](https://github.com/MuneefMumthas/CO452-Muneef-22206529/blob/main/PR1Game/Images%20for%20PR1/Muneef-PR1-ClassDiagram-1.jpg)
![PR1 Class Diagram 2](https://github.com/MuneefMumthas/CO452-Muneef-22206529/blob/main/PR1Game/Images%20for%20PR1/Muneef-PR1-ClassDiagram-2.jpg)

# Game Testing & Screen Shots

## Screen Shot - Start Menu
![PR1 ScreenShot 1](https://github.com/MuneefMumthas/CO452-Muneef-22206529/blob/main/PR1Game/Images%20for%20PR1/Muneef-PR1-GameStartMenu.jpg)

## Screen Shot - Mid Game
![PR1 ScreenShot 2](https://github.com/MuneefMumthas/CO452-Muneef-22206529/blob/main/PR1Game/Images%20for%20PR1/Muneef-PR1-MidGame.jpg)

## Screen Shot - Pause Menu
![PR1 ScreenShot 3](https://github.com/MuneefMumthas/CO452-Muneef-22206529/blob/main/PR1Game/Images%20for%20PR1/Muneef-PR1-GamePauseMenu.jpg)

## Screen Shot - Game Over
![PR1 ScreenShot 4](https://github.com/MuneefMumthas/CO452-Muneef-22206529/blob/main/PR1Game/Images%20for%20PR1/Muneef-PR1-GameOverMenu.jpg)



# Demonstration

[CO452 PR1 Presentaion and Demonstration](https://bucksnuniversity-my.sharepoint.com/:v:/g/personal/22206529_bucks_ac_uk/Ec6u_QzdoiZMoqYAi5Im2rgBOx2jHhSX1nYRQiZvnPbX5g?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=TQixt9)



# Evaluation
*The student should add five limitations or useful extensions that could be added to the application*
1. Healing can be added to extend play time.
2. Animations can be added for better user experience.
3. A way to let players choose their own key-binds can be added.
4. A boss fight after a certain score can be added to make the game more challenging as players progress.
5. Different types of ammos and powerups can be added.
