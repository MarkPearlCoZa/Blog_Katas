---
layout: post
title: Mars Rover Challenge
tags: Useful
category: General
---

#### The Problem ####

Develop an api that moves a rover around on a grid.  
You are given the initial starting point (x,y) of a rover and the direction (N,S,E,W) it is facing.  
The rover receives a character array of commands.  

----------------------------------------------------------------------------------------------

#### Basic Requirements ####

- Implement commands that move the rover forward/backward (f,b).  
- Implement commands that turn the rover left/right (l,r).  
- Implement wrapping from one edge of the grid to another. (planets are spheres after all)  
- Implement obstacle detection before each move to a new square. If a given sequence of commands encounters an obstacle, the rover moves up to the last possible point and reports the obstacle.  


~~~
The rover is on a 100x100 grid at location (0, 0) and facing NORTH.  
The rover is given the commands "ffrff" and should end up at (2, 2)  
~~~


