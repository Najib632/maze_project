---
layout: page
title: Features
permalink: /features/
---

### 0\. Walls !

In this first part, you’ll have to:

-   Create a window with SDL2
-   Use [raycasting](https://intranet.alxswe.com/rltoken/vRw7CP21mUmKFDdrQjQ2GA "raycasting") to draw walls on your window !
-   You don’t need to be able to rotate the camera during the execution in this part, but you must provide a way to change the angle of the camera in your code to see if it works after recompiling it
-   The color of the walls must be different from the color of the ground/ceil
-   The map doesn’t need to be parsed from a file, but you must provide a way to modify it in your code to see if it works after recompiling it. (e.g. using an array of arrays of integers or characters).

Example:

![](/images/move.png)

In the following images, the camera is the red square, and the visible area is painted in green:

![]()

### 1\. Orientation

In this part, you must draw a different color depending on the orientation of the walls.

-   You must at least draw walls facing `NORTH and SOUTH` in a different color from walls facing `EAST and WEST`.

Example:

![](/images/orientation.gif)

### 2\. Rotation

You must provide a way to rotate the camera during the execution.

-   For example, you can rotate the camera when the `left,right` arrows are pressed on the keyboard.
-   Or you can rotate the camera when the mouse moves, just like a FPS game !

Example:

![](/images/rotation.gif)

### 3\. Move

You must provide a way to move the camera during the execution.

-   For example, you can move the camera when the `w,a,s,d` keys are pressed on the keyboard.

Example:

![](/images/move1.gif)

![](/images/move2.gif)

### 4\. Ouch !

In this part, you must handle the collisions of the player (yes, let’s call the camera `player` now, it’s getting serious) with the walls.

-   The player must not be able to enter walls
-   You can make the player slide on the walls instead of just stop it.

### 5\. Parser

In this part you must implement a parser to get the map from a file.

-   You are free to define the standards of your map (The character for a wall, the character for nothing, the extension of the file if you want, …)
-   Your program will need a parameter to run which will be the path to the map file

### 6\. Draw the map

In this part, you must draw the map on the window.

-   You’re free to draw the map where you want, with the color you want, …
-   You must provide a way to enable/disable it during the execution
-   Include the player’s line of sight in the map

### 7\. Coding style + Documentation

-   Check if you code fits the [Holberton School coding style](https://intranet.alxswe.com/rltoken/R15Tf-sVTHL3SWCnEQ7bog "Holberton School coding style").
-   Check if your code is well documented and respect the [Holberton School documentation format](https://github.com/alx-tools/Betty/blob/master/kernel-doc.pl "Holberton School documentation format")

You can check all of this by yourself, just follow the instructions on [this repository](https://intranet.alxswe.com/rltoken/f6sw5PyQ4Mj4FUVBRdAfXg "this repository")

**Be careful**

The check will be done on each file present on your turn in repository. Even the files that was not required. So don’t forget to always keep your turn in directory clean.

### 8\. Textures

In this part you have to add textures on your walls !

Example

![](/images/wall_texutres.gif)

### 9\. Multi task !

Add a way to move on several directions and rotate in the same time. Basically in this part you’ll have to handle multiple events on the same frame.

For example, if the keys to move are `w,a,s,d`:

-   If the keys `w` and `s` are pressed in the same time, the player shouldn’t move.
-   If the keys `w` and `d` are pressed in the same time, the player should move forward and right in the same time,
-   …

### 10\. Ground textures

In this part you have to add textures on the ground and/or on the ceiling !

Example

![](/images/ground_textures.png)

![](/images/ground_textures.gif)

### 11\. Weapons

Add weapons textures !

Example

![](/images/weapons.gif)

### 12\. Enemies

Add some enemies !

Example from the game Wolfenstein 3D:

![](/images/enemies.jpg)

### 13\. Make it rain

Add rain and a possibility to stop / start the rain with a key.

### 14\. Extra option

Shadows, special lightning, etc… get creative!

Copyright © 2024 ALX, All rights reserved.
