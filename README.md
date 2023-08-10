﻿# ECE-385-Final-Project

Welcome!

<img width="368" alt="image" src="https://github.com/MeghaEsturi/ECE-385-Final-Project/assets/90225852/20beec92-42e0-49bc-a79b-7c019121fe60">

This final project was completed by Rawnie Singh and Megha Esturi for ECE 385: Digital Systems Labratory in the Spring 2023 semester.


The game is a traffic simulator implemented on a drawing of the UIUC campus. Programmed into the game are obstacles such as pedestrians, red lights, coin collection, and a countdown timer. Each of these obstacles affects whether the players win or lose, and the score they end with. There are two game modes, both have different objectives and rules. Both modes are two player games:
1. 1v1 mode
2. Team Player mode

---------------------------------------------------------------------------------------------------------------------------------------------------------------------

**1v1 mode:**

• Green Car Controls: WASD

• Purple Car Controls: Arrow Keys

• Objective: Drive through the terrain using the respective  keys. The first player to reach the finish line wins.

• Rules:

1. If either car runs a red light, that car will be reset to the starting point and can retry.
2. If a car hits a pedestrian, that car loses. The other car  wins. 

---------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Team Player Mode:**

• Green Car Controls: WASD

• Purple Car Controls: Arrow Keys

• Objective: Drive through the terrain using the respective  keys. Both players must work together to collect all coins in under 30 seconds.

• Rules:

1. If either car runs a red light, that car will be reset to the starting point and can retry.
2. If either car hits a pedestrian, both cars lose.
3. If all coins are collected and both cars cross the finish line **in under 30 seconds**, game won. Otherwise, game lost.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------
Directions to play:
1. Download this repository
2. Create a new Altera Model Sim project with the files from this repository imported
3. Generate BSP
4. Compile hardware
5. Program the FPGA
6. Open the Nios II software component
7. Run confiurations
8. Connect a keyboard to the FPGA I/O board
9. You're ready to play. Good luck!
