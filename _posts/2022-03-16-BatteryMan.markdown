---
layout: post
title: 'Battery Man'
date: '2022-03-16'
categories: UnrealEngine
tags: C++, Beginner, UnrealEgnine
---
![Battery Man Screenshot](https://blog.micahwood.dev/assets/images/posts/BatteryMan.jpg)
We all start somewhere when it comes to learning a new skill. Tutorials that walk you through a process from beginning to end are an excelent way to start gaining some initial confidence. For me Unreal Engine was a natural choice as I wanted to learn game development and C++. So after setting up my development environment and installing Unreal Engine, I set out to discover what tutorials existed that would help me learn and understand how everything works together. After some searching I found an [Unreal Engine C++ tutorial](https://www.youtube.com/watch?v=LsNW4FPHuZE&t=17s&ab_channel=freeCodeCamp.org) provided by freeCodeCamp.org which included three simple games which increase in complexity.  The first of which was a battery collector game I refer to as *Battery Man*. My completed version of the game can be found on my GitHub ([here](https://github.com/eyesowolf/BatteryManCpp))
### Project Overview
*Battery Man* is a very simple 3rd person game where the player runs around a small map collecting "Batteries". The player must collect batteries to survive as there is a charge meter that diminishes over time. If the charge meter reaches 0 the player dies.
### Project Reflection
As someone who has had no previous experience using Unreal Engine it is a very daunting tool. Thankfully the tutor gave clear instructions that allowed me to get comfortable in the user interface relatively quickly. I'll admit I still have no idea where most things are however that is much to be expected of an beginner tutorial.
At times I would run into some strange issues which were mostly simple fixes. A missed checkbox here and there and a few typo's in my C++ code. I think as an initial project it was effective in quickly gaining the confidence required to attempt a more complex project and potentially re-visit *Battery Man* to as a testing ground to impliment new gameplay features outside the tutorials provided.
For now there are also some bugs in *Battery Man* that I don't understand enough about to be able to fix. One example of this is that occasionally the player won't pick up a "Battery" on the first try.
### Project Extension
In order to make sure I had learned something from the tutorial I challenged myself and successfully implimented a score aspect to the UI. Each time the player pickes up a "Battery" the score increases by 1. This could be extended later with the addition of the ability to store a High-Score.
Other possible project extensions could include: a title screen and other menu items; cause Jumping to use more energy; and, impliment sprinting.