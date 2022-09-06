# Biquadris
A two player Tetris-like game where players place blocks and compete to be the only survivor. Written in C++ and using XQuartz by Darian Zhang, Billy Lee,
and Jason Feng.

## Please contact me at d355zhan@uwaterloo.ca for the source code.

Biquadris contains the same blocks as Tetris, which can be moved and rotated by commands. The block rotation is based on the lower left corner of the smallest
rectangle that the block fits in so blocks are rotated around that point. Blocks appear on the top left corner of the board. 

There are 5 levels of difficulty ranging from 0-4. Level 0 spawns blocks based on a sequence file provided when the game is executed while levels 1-4 spawn
blocks randomly with blocks like the S-Block and Z-block having lower odds of spawning in lower levels. 

The game plays by receiving text-based commands from the command line such as *left*, *right*, *down*, *drop*, etc. which can be combined with numbers in front
of commands and shortened like *3lef*. There are also special actions which occur when 2 or more rows are cleared that are imposed on the other player. These
include blind (blocks a portion of the board), force (forces the opponent's block to be one of your choosing), and heavy (any block movement moves it down 2 rows).

The game provides both a text output of the game and a graphical screen. Examples of gameplay are provided below.
