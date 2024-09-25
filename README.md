# Maze Project

## Background Context

The goal of this project is to create a game in 3D using raycasting !

Please have a lot of fun with this project !

![](/images/back_ground_context.gif)

## Requirements

-   All files should be compiled on Ubuntu 14.04+ LTS, using gcc (Ubuntu 4.8.4-2ubuntu1~14.04) 4.8.4
-   Use the **gcc flags** `-Wall` `-Werror` `-Wextra` and `-pedantic`
-   SDL2: `sudo apt install libsdl2-dev`

## Installation
```sh
$ git clone https://github.com/Najib632/maze_project.git
$ cd maze_project
$ gcc -Wall -Werror -Wextra -pedantic `sdl2-config --cflags` ./src/*.c -lm `sdl2-config --libs` -o maze
$ ./maze
```
