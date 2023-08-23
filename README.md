# Dino
Chrome dino AI using the NEAT algorithm

The program takes screenshots of the screen and analyzes the pixel values and detects and avoids obstacles.

The position and speed of obstacles are deduced and passed on to the ml model, which learns generation by generation, by modifying the structure of its neural network, hence called NEAT algorithm, Neural Evolution of Augmented Topologies. And proceeds by selecting the best-fit offsprings for the next generation.

Youtube link: https://www.youtube.com/watch?v=_G8p0Pf9Zko

Programs used: Python
Packages: NEAT

![image](https://github.com/Christian74D/Dino/assets/112863270/bd95e5c5-17fa-4707-9a7f-e0f291e8d125)


INSTRUCTIONS
Install necessary packages before running
Due to different displays, you may have to alter the constants.py, to have the start and stop pixels of the bounding rectangle and restart button before executing main.py
