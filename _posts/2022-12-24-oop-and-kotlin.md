---
layout: post
title:  "Intro to OOP and Kotlin"
date:   2022-12-20 15:11:20 +0400
categories: devblog
---

> This page includes introduction to OOP and Kotlin form week 4.

### Software requirements

Software requirement is a series of despcriptions of what the system should do. It is usually designed for project managers and developers to follow when they are developing a game. Requirements are there to unite ideas and pathways, so that it avoids developers from having different ideas at once. 

### Software requirements need two things

- **User story**
  - User story exaplains what user wants and for what 
  ex) As a user, I want a new memory game so that I can enhance my memory

- **Definition of done**
  - Definition of done outlines all conditions, or set of requirements, that a software product must meet in order to be approved by a user, customer, team, or consuming system.
  - It should be specific and should clearly state what *should* be done and what *shouldn't* be done

### Software requirements for our game

- The game background should always be black.
- The game should start with 3x3 gray square tiles.
- Right above the top left tile, there should be a house icon (same size as the tile), and right under the bottom right tile, there should be a boy and girl sibling icon. 
-There should be a name of the game on the top left corner, and a setting button on the top right corner.
- When the player clicks on the setting button, a rectangular box should appear in the middle of the screen. The box should have the name of the game on the top middle, my record, continue game, and exit button right under the other. There should also be a circular button on the top right corner of the box where the player can turn the sound effect on and off

### Introduction to OOP

OOP, also known as an Object-oriented programming, is a type of programming that emphasizes the identification of classes of objects that are closely related to the methods (functions) that go along with them. It is a computer programming model that arranges the design of software around data, or objects, rather than functions and logic.

![example](https://upload.wikimedia.org/wikipedia/commons/b/be/Oop_2022-12-24_at_4.42.23_PM.png)

This diagram is an example of OOP. The class, which is the blueprint, is the base for the objects, which are the cars. Like this, the blueprint serves as the base for every car, making us be able to make a car more easily just by arranging the base a bit rather than creating a whole ew car.

![example2](https://upload.wikimedia.org/wikipedia/commons/5/53/Car_2022-12-24_at_4.47.08_PM.png)

This is the exercise we did in class. We were given a car and were told to copy it exactly without any guidelines. Then we were given a blueprint of the car and were again told to build a same car. The second time was much easier as we had guidelines and parts of the car that we just had to arrange, while during the first one, we had to draw the whole car out of blank. We were also able to change the details, such as color of the car, easily with the parts and blueprint

### Introduction to Kotlin

![firstkotlin](https://upload.wikimedia.org/wikipedia/commons/e/ef/Kotlin_2022-12-24_at_4.51.28_PM.png)

This is what we did on the first lesson of Kotlin. We learned how to use *app:layout_constraint____to____Of*. We used this code to efficiently place texts and images exactly where we want such as right in the middle.

![carkotlin](https://upload.wikimedia.org/wikipedia/commons/a/a4/Kotlin_2022-12-24_at_4.51.38_PM.png)
![carkotlin2](https://upload.wikimedia.org/wikipedia/commons/0/08/Kotlin_2022-12-24_at_4.51.48_PM.png)

On the secong lesson, we used OOP to make out object 'car' do different things. We learned how to change the color, model name, and speed. We also used *while* code to change the car's speed when it accelerates and when it's on brake. Then we tested if the code was working by printing them, which stated the car's color, message, and speed. 

![test](https://upload.wikimedia.org/wikipedia/commons/3/3d/Kotlin_2022-12-24_at_4.52.23_PM.png)
This is what they printed when we ran the test.