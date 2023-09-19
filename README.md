# cub3d

cub3D is a school project that emulates the raycasting techniques used in classic first-person shooter games like Wolfenstein 3D. It creates a 3D perspective from a 2D map and allows you to navigate through maze-like environments. Made with https://github.com/AxelBadam

## Features

- Raycasting rendering engine
- Textured walls and sprites
- Player movement with keyboard and mouse input
- Collision detection
- Map parsing from a configuration file
- Adjustable resolution and textures
- Mini-map display

## Installation

1. If you have 42 homebrew replace this line in the makefile:
```
libmlx42.a -Iinclude -lglfw -L"/opt/homebrew/Cellar/glfw/3.3.8/lib/"
```
to this:
```
libmlx42.a -Iinclude -lglfw -L"/Users/$(USER)/.brew/opt/glfw/lib/"
```

2. Check dependencies for the MLX42 graphics library (depends on your OS)

https://github.com/codam-coding-college/MLX42#installing-the-dependencies

3. Clone the cub3D repository:

```
$ git clone https://github.com/eetukoljonen/cub3D.git ; cd cub3d
```

4. Run `make`

-installs and builds the MLX42 and the program

## Usage
   
```
$ ./cub3D test_maps/working_maps/simple_map.cub
```

-use the WASD keys to move forward, backward, and sideways. Right and left arrow to turn.

-press M to toggle mouse turn

-press ESC to exit the game.

-create your own maps or modify the existing ones in the test_maps/working_maps directory with the provided textures.

![cub3d video](https://github.com/eetukoljonen/cub3D/assets/120648288/99c84f74-ff60-4ba8-b9f3-94a67326ddfe)


