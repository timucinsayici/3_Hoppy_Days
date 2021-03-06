﻿# Discovering Godot - The Game Engine You've Been Waiting For
## Section 3 - Hoppy Days
This is GameDev.tv's guide to the free and open source Godot game engine.  Learn the free to use, free to modify, free to create engine with one of the most successful online game develeopment educational groups out there.

You're welcome to download, fork or do whatever else legal with all the files! The real value is in our huge, high-quality online tutorials that accompany this repo.

## In This Section
Create a fun word game based on Madlibs while you get to grips with GDScript and the foundations of scripting.   (Our ref: HD_GDT)

## How To Build / Compile
This is a Godot project. If you're familiar with source control, then "clone this repo". Otherwise download the contents and place them in an empty folder that's in a convenient place.  Open Godot, ``Import Project`` and navigate to the folder you just made.  select ``project.godot`` and you're good to go.

No compiling necessary!  This is Godot, after all.

This branch is the course branch, each commit corresponds to a lecture in the course. The current state is our latest progress.

## Lecture List
Here are the lectures of the course for this section...

### 1 Planning Hoppy Days
#### In this video (objectives)…
1 Discuss the game we're making 
2 Examine the features we'll need to create

#### After watching (learning outcomes)…
Plan out the central mechanics and feeling of our 2D platformer game!


### 2 Downloading the Assets for Hoppy Days
#### In this video (objectives)…
1 Download and Import the game assets
2 Create a Scripts folder
3 Tour the file structure for Hoppy Days

#### After watching (learning outcomes)…
Understand how to plan the file system for a new project


### 3 PhysicsBody2D - Making a Character
#### In this video (objectives)…
1 Create a ``KinematicBody2D`` character
2 Define custom player inputs
3 Move the character left and right using player inputs

#### After watching (learning outcomes)…
Know the different kinds of ``PlayerBody2D`` nodes, Understand when to use ``move_and_collide()`` and ``move_and_slide()`` and how to use ``and`` and ``not`` in if statements

### 4 AnimatedSprite - Making Bunny Run
#### In this video (objectives)…
1 Create an `AnimatedSprite`` node
2 Set up animations
3 Call animations based on which way the player is going
4 Flip the sprite to match the direction to player is heading in

#### After watching (learning outcomes)…
Learn about ``AnimatedSprite`` nodes, how to set up and call animations in them and how to flip the sprite in the script

### 5 Jumping
#### In this video (objectives)…
1 Instance a scene
2 Apply gravity to the player
3 Allow the player to jump

#### After watching (learning outcomes)…
Learn how to instance a scene, change the main scene of the game, make the player fall and let the player jump!

### 6 Cleaning Up The Player Code
#### In this video (objectives)…
1 Move the animation logic to the `AnimatedSprite` node
2 Explore the concept of Elegant Code

#### After watching (learning outcomes)…
Understand the principle of one script being in charge of one thing

### 7 Tilemaps - Making a Level

#### In this video (objectives)…

1 Make a Tilemap
2 Make a Camera2D


#### After watching (learning outcomes)…

Learn the awesome power of Tilemaps 

### 8 is_on_ceiling()
#### In this video (objectives)…

Stop Bunny from floating along the ceiling

#### After watching (learning outcomes)…

How to use ``is_on_ceiling()``

### 9 Parallax Backgrounds
#### In this video (objectives)…

1 Create a ``ParralaxBackground`` node
2 Make multiple ``ParralaxLayer`` nodes
3 Tweak the values to fit our game

#### After watching (learning outcomes)…

Learn the secrets of Parallax Background in Godot!


### 10 The Game Over Screen
#### In this video (objectives)…

1 Create a Game Over Screen
2 Trigger Game Over when Bunny falls too far
3 Allow the player to start again

#### After watching (learning outcomes)…

Create a game over screen and get a brief introduction to control nodes!


### 11 Area2D - Making Spike Hazards
#### In this video (objectives)…

1 Make an Area2D
2 Instance a Spike Scene
3 Make the level challenging

#### After watching (learning outcomes)…
How to use Area2D to make level hazards


### 12 Control Nodes - Making a GUI
#### In this video (objectives)…

1 Use Anchors and Control nodes 
2 Make a flexible GUI
3 Change the way Hoppy Days deals with Aspect Ratio

#### After watching (learning outcomes)…
Understand the basics of ``Control`` nodes and some easy tips for flexible GUI

### 13 GameState.gd
#### In this video (objectives)…

1 The Single Responsibility Principle
2 Create a script to handle the game's rules
3 Call a function from a child node

#### After watching (learning outcomes)…

Learn the Single Responsibility Principle and how to organize your game around it.

### 14 Global Scripts
#### In this video (objectives)…
1 Create a singleton
2 Move node paths to the singleton
3 Allow nodes to be moved and renamed without breaking anything

#### After watching (learning outcomes)…
Learn how to use a global script to solve the script referencing problem!

### 15 Adding Lives
#### In this video (objectives)…
1 Create a ``starting_lives`` variable and a ``lives`` variable
2 Update ``lives`` when Bunny is hurt
3 Make bunny jump up when hurt

#### After watching (learning outcomes)…
Add lives to our game!

### 16 Updating the GUI
#### In this video (objectives)…

1 Create an update_GUI() function
2 Display the current number of lives to the player
3 Update the GUI when hurt

#### After watching (learning outcomes)…
Keep the GUI up to date

### 17 AnimationPlayer - Making Coins
#### In this video (objectives)…

1 About the ``AnimationPlayer`` Node
2 Introducing Keyframes
3 Calling functions in ``AnimationPlayer``

#### After watching (learning outcomes)…
Use AnimationPlayer to make coins work!

### 18 Polishing the GUI
#### In this video (objectives)…

1 Giving the player feedback when coins and lives values change
2 Allowing Bunny to gain extra lives

#### After watching (learning outcomes)…
Control multiple animations in a single function by calling arguments

### 19 AudioStreamPlayer - Bring the Noise!
#### In this video (objectives)…

1 Add background music to our game
2 Add sound effects for jumping, coin pickup and pain

#### After watching (learning outcomes)…
Learn to use ``AudioStreamPlayer`` nodes!

### 20 Jump Pads
#### In this video (objectives)…

1 Create Jump Pads
2 Use a ``Timer`` node to reset Jump Pads

#### After watching (learning outcomes)…
How to use Timer nodes to trigger events

### 21 Enter the Spikeman
#### In this video (objectives)…

1 Create a Spikeman NPC
2 Use ``AnimationPlayer`` to bring Spikeman to life

#### After watching (learning outcomes)…
How to use Animaitn Player to create NPC behaviours

### 22 Fixing the Coin Bug
#### In this video (objectives)…

1 Stop the Player from picking up the same coin multiple times

#### After watching (learning outcomes)…
How to stop something triggering repeatedly

### 23 Making the Cloud NPC
#### In this video (objectives)…

1 Create an NPC that can fire a projectile
2 Use ``Raycast2D`` nodes
3 Check what body is in an ``Area2D``

#### After watching (learning outcomes)…
How to detect if a player is being aimed at and spawn a projectile at the player

### 24 Particles and a Portal
#### In this video (objectives)…

1 Create a Portal to let Bunny win the game
2 Link the Portal to a Victory scene
3 Decorate the Portal with the ``Particles2D`` node

#### After watching (learning outcomes)…
A quick introduction to the ``Particles2D`` node!

### 25 Polishing the Game: The Jump Pad Bug
#### In this video (objectives)…

1 Make sure the Jump Pad works consistently
2 Limit fall speed

#### After watching (learning outcomes)…
Using ``clamp()`` to keep a value within range
