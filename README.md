# Gruniożerca for Gamebuino Meta!
Gruniożerca Meta is a port of the "classic" Gruniożerca game, originally for the NES.
Created by Dark Archon (arhn.eu, code) and Neko (graphics). Original concept by Łukasz Kur.

##Please note this code is WIP and subject to change!

## What is this?
Gruniożerca for Gamebuino Meta is a simple sample project for the Gamebuino Meta system.
A Windows "port" will be made available soon, as there is no fully featured PC emulator of the console available.

The goal of the project was to create a simple Gamebuino game which would utilize most of the common features of the system.

Included are:
1. gruniozerca-meta.ino -- the main source file for the Polish version
2. gruniozerca.bin -- a precompiled .bin file for the console
3. /SFX -- folder containing sound

And optional:
4. /GFX - source files for the images used in the game

## Game Features

The project aims to showcase most of the basic Gamebuino functions:
- A score counter with a working Hi-score function and score saving
- A main manu created using a custom script for bigger flexibility
- Bitmap manipulation
- Sound support - both built-in SFX as well as wav files
- Game Over, Hi-Score screens and more

## How to play?
Move Grunio around with the left and right buttons. Orange and white carrots will fall from the sky. The goal is to "eat" as many as possible. But there's a catch: Grunio can only eat carrots of the same color as his fur! To change Grunio's fur color press "A". Miss three times and it's game over!
Press "Menu" to forfeit.

## How do I use the source code?
You can open the "gruniozerca-meta.ino" file in the Arduino IDE, to see what the source code looks like.
Please note that the game is far from complete and currently contains a lot of unused code and generally needs a lot of tidying.
Sound support is also quite glitchy and rudimentary at this time.

The Arduino IDE will require the Gamebuino Meta libraries to run.

You can also use the precompiled bin files to play the game on the emulator and/or Gamebuino Meta compatible consoles.
Please note that currently no Gamebuino Meta emulator supports all the features.
Most notably SD card loading support is missing meaning no sound and no remote graphics loading!

## How do I play it?
Copy the gruniozerca.bin file and sfx folder into a /gruniozerca folder on your SD card root.
The game should now be available to play in your Gamebuino Meta launcher. Although the launch icon is still missing.

You can also play the game online, in an emulator!
Drop the gruniozerca.bin file onto this emulator: https://gamebuino.com/creations/meta-emulator
Please note: The emulator is not feature complete. Sound and saving support will be missing.

## I want to learn more!
Gruniożerca Meta was created for an arhn.eu video on building and programming a Gamebuino Meta.
Visit arhn.eu (Polish) for more information.
