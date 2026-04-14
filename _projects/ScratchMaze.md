--- 
layout: page
title: "Scratch Maze"
description: "An interactive maze built in Scratch demonstrating control flow, variables and user interaction"
img: assets/img/Scatch.png
category: work
---

## Overview ## 

This project is an interactive maze game built in Scratch as part of KNES 381. Demonstrating progamming concepts including control flow, conditional logic, variables and user interaction, without the use of traditional code.

The maze runs on logic-based programming. Movement, collision, and the win condition are driven by rules and checks that continuously run in the background, forming a complete control loop. 

---

# How it Works ## 

The maze runs through a continuous control loop that runs every frame 

1. **User input** is detected by checking which directional key is being pressed
2. **Sprite movement** is detected and updated in the direction of the key press
3.  **Collision is checked** to test if the sprite is touching a wall colour
4.  **Condition evaluation** occurs if touching a wall, and the sprite is restricted from moving to that area
5.  **Enemy sprite** logic runs and continuosly follow the player's position around the maze
6.  **Enemy collision is checked** throughout the game, if the enemy touches the player, the player loses a life and resets to the start.
7.  **Lives variable** is updated; losing 3 lives will restart the game
8.  **Krabby Patty** collsion is checked. Upon touching the patty, the player will be sent to a second screen
9.  **Second screen** logic runs, upon collection of the 2nd patty, a win screen is triggered
10.  **Win condition is checked** upon reaching the end zone, if completed a win sequence is triggered

This loop runs constantly while the game is running, making it fully responsive to user input. 

---

## Programming Concepts Used ##

Concept | Description
------------- | -------------
**Control Flow** | The sprite continuously checks for wall collisions and responds
**Conditions** | If touching a wall — reset position; if reaching the end — trigger win
**User Interaction** | Arrow key inputs move the sprite through the maze
**Variables** | Timer or move counter tracking progress
**Anti-Cheat** | Prevents the player from bypassing maze walls

---

## Play the Maze

<iframe src="https://scratch.mit.edu/projects/1286619322/embed" allowtransparency="true" width="485" height="402" frameborder="0" scrolling="no" allowfullscreen></iframe>

---

## Links
- [View on Scratch](https://scratch.mit.edu/projects/1286619322)
