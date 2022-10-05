# Robot Finds Kitten

Simon Carless once described robotfindskitten as "less a game and more a way of life ... It's fun to wander around until you find a kitten, at which point you feel happy and can start again". I don't think I could have said it better myself!

## Overview

---

Rfk is a game in which the player seeks to find the kitten among many artifacts. That's it!

## Rules

---

Rfk is played according to the following rules.

- Several artifacts are randomly positioned on the screen.
- Each artifact has a randomly chosen symbol and message.
- The player moves the robot (#) around the screen.
- When the robot touches an artifact, the message is displayed.
- If the robot touches the kitten, "You found kitten!" is displayed.
- There is no winning, losing or game over. This is the zen of rfk.

## Interface

---

![RFK Interface](https://user-images.githubusercontent.com/44569083/194060042-020e4ad7-433a-4984-b55b-06cac904f8d4.png)

## Getting Started

---

Make sure you have Python 3.8.0 or newer and Raylib Python CFFI 3.7 installed and running on your machine. You can install Raylib Python CFFI by opening a terminal and running the following command.

```
python3 -m pip install raylib
```

After you've installed the required libraries, open a terminal and browse to the project's root folder. Start the program by running the following command.

```
python3 rfk
```

You can also run the program from an IDE like Visual Studio Code. Start your IDE and open the
project folder. Select the main module inside the hunter folder and click the "run" icon.

## Project Structure

---

The project files and folders are organized as follows:

```
  root              (project root folder)
  +-- rfk           (source code for game)
    +-- data        (data files for game)
    +-- game        (specific game classes)
    +-- __main__.py (entry point for program)
  +-- README.md     (general info)
```

## Required Technologies

---

- Python 3.8.0
- Raylib Python CFFI 3.7

## Authors

---

- Reuel Magistrado (mag21010@byui.edu)
