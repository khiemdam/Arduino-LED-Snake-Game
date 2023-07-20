<!-- Shields from shields.io -->
![Author][author-shield]
[![LinkedIn][linkedin-shield]][linkedin-url] [![Handshake][handshake-shield]][handshake-url] ![Status][status-shield]

# Arduino LED Snake Game

### A self-playing "Snake" game running on an LED grid/board. This program utilizes c++ for the LED control, game logic and rule based AI. The hardware is powered by an Arduino microcontroller, which my c++ code runs on.

## Table of Contents
* [Motivation](#motivation)
* [Technologies and Supplies](#technologies-and-supplies)
* [Installation](#installation)
* [How To Use](#how-to-use)
* [To-Do List](#to-do-list)
* [Status](#status)
* [Credits](#credits)

## Motivation

This is a side project written in c++ to help me decorate my room and try out something new. This is my first time working with LEDs through Arudino, so I thought it would be fun to learn something new. This is mainly a side hobby to apply my knowledge of c++ to make something cool!

The main challenge will be implementing a snake game and an AI that is able to play that game.

## Technologies and Supplies
* C++
* Any IDE that supports Arduino (I used VSCode)
* WS2812B RGB LED Strips (144 pixels)
* Arduino Leonardo
* Picture frame and foam board

## Installation
Navigate to your desired directory. In your shell/terminal, type in the following:

For HTTPS
```
git clone https://github.com/khiemdam/Arduino-LED-Snake-Game.git
```
For SSH Keys
```
git clone git@github.com:khiemdam/HTML-Recipes-Website.git
```

## How To Use
To wire up and assemble the physical components, you can find the instructions at _____ (TODO)

After assembling the LED light board, on your IDE, select your Arduino board. Compile the code to make sure it works, then upload the code to the Arduino board. The snake game should run automatically!

## To-Do List
- [ ] Building the LED Board
    - [X] Buy/Recycle Supplies
    - [X] Cut LEDs into strips
    - [ ] Solder LEDs together, connected with cables
    - [ ] Put LEDs in grid on foam board
    - [ ] Put inside frame
- [ ] Create Snake Game
    - [ ] Create matrix/grid class to control LEDs properly
    - [ ] Create snake class
    - [ ] Create game class
- [ ] Create Rule Based AI
    - [ ] TODO

## Status
Currently busy with balancing work, life, and trying to squeeze in time for coding. Will finish assembling board and starting on the Snake Game.

## Credits
* TODO

<!-- Links & Images -->
[author-shield]: https://img.shields.io/badge/Author-Khiem_Dam-555?style=for-the-badge&color=999
[linkedin-shield]: https://img.shields.io/badge/LinkedIn-555?style=for-the-badge&logo=linkedIn
[linkedin-url]: https://www.linkedin.com/in/khiemd/
[handshake-shield]: https://img.shields.io/badge/Handshake-555?style=for-the-badge&logo=handshake&logoColor=white
[handshake-url]: https://app.joinhandshake.com/stu/users/31441591
[status-shield]: https://img.shields.io/badge/status-WIP-555?style=for-the-badge&color=FFA500