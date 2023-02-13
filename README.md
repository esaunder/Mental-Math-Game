# Mental-Math-Game
A turn-based game where you need to answer math questions to attack the enemy made using Java. ([Demo Video](https://youtu.be/iMbGX3d2MWY))

By [Ethan Saunders](https://github.com/esaundere) 
Course: Computer Science ICS4UD (Grade 12 IB program course)  
Date: February 16th, 2018  
Grade: 96% (level 6)

!(assets/TenaciousTanksGif.gif)  

## Table of Contents
[1. Intro](#Intro)  
[2. Gameplay](#Gameplay)  
[3. Environment Setup](#Environment-Setup)  
[4. How to Play](#How-to-Play)  
[5. Results](#Results)  
[6. Next Steps](#Next-Steps)  
[7. Development Changelog](#Development-Changelog)

## Intro

I was inspired to make this game for my IB project with the goal to make an enjoyable way to practice mental math for kids. The game has basic turn based gameplay but to properly attack, the user must answer a math question in a set amount of time. Various difficulties were implemented to ensure people of different skill levels can enjoy the game.

This game was made using Java. It utilizes basic object-oriented programming and a variety of other techniques.

## Gameplay

Check out the demo video for this project [here](https://youtu.be/iMbGX3d2MWY)!

![Tenacious Tanks Main](assets/TenaciousTanksMain.png)  
![Tenacious Tanks Game](assets/TenaciousTanksGame.png)

## Environment Setup

To successfully run this project, please follow these steps to set up your environment:

1. Any IDE that runs Java (I recommend [IntelliJ IDEA](https://www.jetbrains.com/idea/), [JCreator](https://www.deepcrazyworld.com/how-to-download-jcreator-pro/) or [VS Code](https://code.visualstudio.com/download))
2. Java SE 8 (which includes JDK 1.8.0_333) ([Download from Oracle](https://www.oracle.com/java/technologies/javase/javase8u211-later-archive-downloads.html))
3. Ensure your IDE is configured to use the above version of Java SE and JDK

## How to Play

Simply click on the buttons and enter data into the text boxes to play.

Run the [mainCoding.java](mainCoding.java) file to play!

You can save your data at any time and if you want, you can edit your save data in the file Save.txt.

## Results

This project turned out quite well considering my limited knowledge of Java when starting this project.

I learned how to utilize a variety of different Java classes and developed my problem solving and troubleshooting skills through the development process which has set me up for success in my university programming courses.

**Grade: 96% (level 6 from IB)**

## Next Steps
Some potential improvements that I can see myself making in the future:

- An expanded shop that allows a player to upgrade their damage and defense
- An improved health bar to allow for more flexibility when programming encounters
- Improved animations as the current animations are not good (simply shifting images)
- Add a player character to the screen and possibly even add other party members to allow for harder fights and more diverse attacks
- Add special enemy attacks and a guard ability to make combat more complex
- Allow the player to move around a map instead of following the on-the-rails combat encounter, transitioning into a proper turn-based rpg

These changes are significant but they will definitely improve the game by a large amount.

## Development Changelog
November 12th, 2019: Project outline drafted

November 15th, 2019: I researched how to make a GUI in Java

January 24th, 2018: Tailai has PISKEL and PNG files created for basic 2-player movement.

January 25th, 2018: Tailai updated TenaciousTanks.java to test out KeyListener.

January 26th, 2018: Cameron has map generation with an added background JPG file.

January 27th, 2018: Cameron debugged map generation and integrated with TenaciousTanks.java.
Tanks now fall from the sky on initial startup.
Rescaled tank images can now sit on the terrain while moving and at rest.
Began tank object class (deals with health, damage, etc).

February 5th, 2018: Cameron finished angle and movement inputs from users.

February 6th, 2018: Cameron created the turning process. Each player has a selection phase and a shooting phase.
Tailai created and implemented turn images for each user.

February 7th, 2018: Cameron finished the movement restriction for tanks. (Can only move up to 50 pixels left or right during the selection phase)

February 8th, 2018: Cameron started bullet class.  
Bullets now fly using power, angle, and positions given by users.  
Bullets are affected by "gravity" and end turn when it collides with ground and tank rectangles.

February 9th, 2018: Tailai made an Update to GamePanel and TenaciousTanks. The game now has text displays and damage is calculated with collisions.  
Cameron created power for bullets. Users can now select a power between 0 and 100.

February 12th, 2018: Tailai made an Update to all files, allowing players to actually win the game. No Play Again button yet though...

February 16th, 2018: Cameron created the menu and instruction screens. Players can now go through the menu and instructions before starting the game. When the game finishes, players can choose to play again (all variables will reset) or exit the window.  
Tailai and Cameron added explosion sprites for bullet impacts. Added a new Python 3.2 file that splits sprites into png. files. Added explosion animation and polished up User Interface. Comments added to code.

February 16th, 2018: Project finished.
