# SnakeGame
Popular Snake Game written in C

## Overview
The classic snake game played via the terminal.
Example game state:
```
##############
#            #
#    dv      #
#     v   #  #
#     v   #  #
#   s >>D #  #
#   v     #  #
# *A<  *  #  #
#            #
##############
```
The grid has the following special characters:

- ```#``` denotes a wall.
- (space character) denotes an empty space.
- ```*``` denotes a fruit.
- wasd denotes the tail of a snake.
- ^<v> denotes the body of a snake.
- WASD denotes the head of a snake.
- x denotes the head of a snake that has died.

Each character of the snake tells you what direction the snake is currently heading in:
- w, W, or ^ denotes up
- a, A, or < denotes left
- s, S, or v denotes down
- d, D, or > denotes right

## What I learned
- using pointers in C
- manual memory management in C using `malloc`, `calloc`, and `free`
- writing unit and integration tests in python

##Acknowledgements
This project was part of my coursework in UC Berkeley's CS61C Computer Architecture course. More details regarding the documentation of this project can be found [here](https://cs61c.org/fa22/projects/proj1/#conceptual-overview). Since this is a class project, I cannot post the code publicly, but can make it available upon request.
