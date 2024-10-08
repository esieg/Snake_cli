# Snake
ith new Functions develop for Labyrinth, it's not a big step to create a Snake-Game, so lets do it.

## Compile
I use simple g++ for compiling and add the ncurses-Header
> g++ -std=c++17 -o Snake Snake.cpp -lncurses

## Start the game
Use this in the folder containing the Snake-Binary (Terminal should have at least 42x42 [columnsxrows])
> ./Snake
or 
> ./Snake -s/--simple
to start the game in the simple mode. Here you can give the snake directly the direction you want here, no need for a right/left steering with perspectives. 

## Steps
### Clear Screen
* (/) Takeover from Labyrinth

### Enable RAW-Mode
* (/) Takeover from Labyrinth

### Draw "Cage"
* (/) at the outerlines of the Playfield
* (/) use suited characters

### Draw Snakehead to a Cursorpositopn
* (/) given as Row-Col-Vector

### Steer the Snake
* (/) trough arrow keys left/right

### Move the Snake
* (/) by a static framerate
* (/) increase the framerate when the Snake grows

### "Eat Fruit"
* (/) Fruit appears at random position
* (/) let the Snake grow
* (/) increase Score by 1

### Collisionrecognition with Wall and Snake
* (/) draw "Walls" as obstacles
* (/) end game when the snake hit the wall
* (/) end game also when snake hits hisself

## Styleguide
a little Styleguide to get a constant naming
* **CLASS**: full capitalized
* **functionsAndMethods**: camelCase
* **variables_and_properties**: snake_case
* **CONSTANTS**: full capitalized