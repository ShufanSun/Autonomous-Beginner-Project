# Autonomous-Beginner-Project
The beginner project for wisc autonomous club

Methodolgy: 
First remove all other colors except for redness, because the cones are red. 
Then clearing the pieces of scattered redness that are distracting.
Binarize the image to 0s and 1s
Search from left to get the leftmost cone
search from middle to left to get the right most cone of the left line
repeat the same thing to the right line of cones
connect the coordinates of the cones to form the path view


What did you try and why do you think it did not work.
I tried to let matlab plot the line directly on red objects but it got 
confused and messed up.
Then after cleaning up I realized that the door was red...
    so I cleaned up the door by coloring it with black(0 because I 
binarized it)
I tried to plot by directly calling the fields, but it didn't work out
so I first named the centroid before I call its coordinates

What libraries are used:
image processing tool
