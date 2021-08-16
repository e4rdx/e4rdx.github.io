---
layout: post
title:  My GameDev history
date:   2021-08-07 19:33:42 +0200
show_excerpt: yes
excerpt: An overview of the games I've created so far
categories: GameDev
---

Yes, I started programming because I wanted to create some games. It didn't took long to find out that it's not as easy as I thought. After a couple of fails, I moved on to python. But that's a different story.\\
One day, when I had a lot of time and a lot more programming experience, I decided to try again. So I've choosen the Unreal Engine, the obvious *best* choice for complete beginners...\\
So I played around to understand some of the tools. After some very chaotic learning worlds I thought a first project would be great.

# The arena shooter
The ideas was to have an arena where the player has to defeat waves of enemys. The implementation was not ... that good. Look at this professional map:
<img src="/assets/ArenaShooter/map.jpg" alt="image"/>
But there was a player with movement and a shooting system:
<img src="/assets/ArenaShooter/gameplay.jpg" alt="image"/>
There was also a small main menu I was very proud of.\\
List of features:
* AI spawner
* AI following and attacking player
* Shooting system for player to attack AI
* Health and regeneration system for player
* Ammo and reloading
* Player and AI death
* Respawn

# Defend the town
Lets move on to the next fail. After some work on the shooter, I was bored of it. So I had a new idea: Place some towers on a map and at the end a small town. Then, spawn waves of enemys and let the player defend the towers, like a third-person tower defence game:
<img src="/assets/TownDefender/Map.jpg" alt="image"/>
The red spheres are the locations of the towers to defend. The AI's are starting from the left and the town should be at the right. There's a lake in the middle and a valley at the left.
There were two types of enemys, destroying the walls and/or attacking the player:
<img src="/assets/TownDefender/Gameplay.jpg" alt="image"/>
Here's my main menu:
<img src="/assets/TownDefender/MainMenu.jpg" alt="image"/>
One thing I've learned: Good lightning is hard.
Now, something I'm very proud of: A skill tree:
<img src="/assets/TownDefender/Skilltree.jpg" alt="image"/>
You are able to unlock those things with skillpoints! There is a system for saving and loading the skilltree!\\
List of features:
* Main menu
* Pause menu
* Settings for window size
* Skilltree(One Character to unlock)
* Two playable characters, only one that can attack
* AI wave spawner
* Enemys walking from tower to tower to destroy it
* Two types of enemys
* Enemys with gun shooting at player or building
* Close combat enemys only attacking buildings
* Game over / Game won

# Multiplayer shooter
This is the project which became Clone League later on, which is my greatest project so far. So it deserves its own blog entry!

# LibGDX
I had a short look at this and wanted to create a SpaceInvader type of game for mobile. When I got a controllable spaceship I stopped the development because I foud out about Godot. If you want to create games with Java or Kotlin I can definitly recommend LibGDX!

# Restart with Godot Engine
After stopping the development of CL I did not much about GameDev for a long time, until I found out about Godot Engine. One day I got a video suggestion from youtube for video about Godot and when I saw it, I immediately loved the engine. In my opinion it is probably one of the best choices for creating 2D games. Now I'm currently working on InfinityShapes.