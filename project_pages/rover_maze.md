# Rover maze

TODO: Interactive code (replit) button

TODO: GitHub repository button

| [Interactive code (replit)](https://replit.com/@WrenMcQueary/rover-maze#.replit)      | [GitHub repository](https://github.com/WrenMcQueary/rover-maze) |
| :---:        |    :----:   |

## Summary

While working at KID Musuem, I developed this game to teach students how to design finite state machines for use in robotics classes and workshops.  I used Prim's algorithm to generate random mazes to be solved by a robot with limited sensing abilities.

The robot is ladybug-shaped, with two antennae.  For each antenna, it can sense whether that antenna is touching a wall.  The robot remembers itself to be in one of 4 internal states, and can take actions and switch between states based on rules written by the player and what its antennae sense.

The objective of the game is to design a finite state machine such that the robot can solve any maze you throw at it.  The "New Maze" button can be pressed to generate an unlimited number of random mazes for the robot to solve.

Note: Replit has been a bit inconsistent about supporting windows created by tkinter.  If you can't get the project to run on Replit, consider cloning it with GitHub and running it locally on your machine.

![Code snippet](/images/projects/rover_maze/code_snippet.png)

## Skills gained

I had recently learned unified modeling language before starting this project.  Seeing this project as the perfect opportunity to practice this skill, I maintained a UML graph for the project while developing it, using the graph as a guide for where to create classes, functions, and so on.

![UML](/images/projects/rover_maze/uml.png)

<br/><br/>

wren.mcqueary@gmail.com
