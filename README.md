# Math-w-py
Math probs solved in python
You are developing an Alien Invader Shooting Game. Your spaceship is in a fixed position. 
Alien ships appear in random locations on the 2D screen. 
At any point in time, there will be only two alien ships on the screen. Your duty is to find the nearest alien ship to shoot first.

Given the (x,y) coordinates of your spaceship as well as those of the two alien ships, 
your task is to compute the Manhattan distance between your spaceship and each of those enemy ships and decide the ship to shoot first based on the smallest distance. 
If the distances are the same, you will shoot enemy ship 1. Otherwise, you will shoot the ships with the shortest distance. 
Manhattan distance is calculated as |x - x1| + |y - y1| between two points (x,y) and (x1,y1).

Write a Python program to identify the closest enemy ship.

There will be three lines of input. The first line is the x and y coordinates of our spaceship. 
The second line is the x and y coordinates of the first enemy ship. The third line is the x and y coordinates of the second enemy ship.





If the closest enemy ship is 1 or both of them are at the same distance, the output is 1. Otherwise, the output is 2.
