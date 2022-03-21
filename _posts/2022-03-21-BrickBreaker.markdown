---
layout: post
title: 'Brick Breaker (Arkanoid) '
date: '2022-03-21'
categories: UnrealEngine
tags: C++, Beginner, UnrealEgnine
---
![Brick Breaker Screenshot](https://blog.micahwood.dev/assets/images/posts/BrickBreaker.jpg)
Today I began my 2nd ever Unreal Engine project which utilizes both Blueprints and C++ to make the game. I'm still following the same tutorial as the Battery Man project which can be found [here.](https://www.youtube.com/watch?v=LsNW4FPHuZE&t=17s&ab_channel=freeCodeCamp.org) This time instead of using Unreal Engine's "Starter Content" I'll be beginning with a completely blank project. Over the course of this project I'll be uploading my progress to my GitHub ([here](https://github.com/eyesowolf/BrickBreaker))
### Project Overview
The concept of Brick Breaker as a game should be relatively familiar to most people as the game has been around since 1999. In this version of the game the player will control a paddle at the bottom of the screen and bounce a ball upwards to break the blocks. If the player's ball reaches the bottom of the screen and doesn't bounce off the paddle the ball will be reset to the center of the screen.
### Project Reflection
Taking the experience gained in the first tutorial to I felt much more comfortable with the workflow of switching between Visual Studio and Unreal Engine. Starting the project from an empty template was quite dawnting however with the experience gained in the first tutorial in combination with the tutorial explinations It wasn't long until the project was complete. 
Due to the fact that much more of this game was written in C++ than my last excersize ([here](https://blog.micahwood.dev/unrealengine/2022/03/16/BatteryMan.html)) the game is quite buggy. For example, initially if the ball was accellerated via hitting it with the side of the paddle occasionally physics wouldn't register collisions. This specific example was fixed relatively easily though by decresing the maximum physics delta time. There are still quite afew bugs that need fixing in this project:
* Ball can move the paddle down below the map removing limits to how the paddle can move and even moving the paddle to below the ball despawn point making the game impossible
* Score indicator not working and not fully implimented
* Ball can accellerate so fast that it can escape the bounds of the level

### Project Expansion
I believe that it is important to expand on lessons given in tutorials so that you can understand more about the implimentations and systems in use. Initially I believed that adding a Score indicator to the game would be a simple task however at this stage nothing I have tried has worked (Other than getting the score UI to appear during play). Other expansions on this project I intend to complete are: Multiple levels, Menu Screen with level select, High Score, Save Files, Power-Ups.
At this stage I don't think I am compotent enough in UE to complete many of these however with the third and final tutorial in the Beginner UE series that I am following I think I might be able to impliment some of these features (Score, High Score, and Power-Ups)