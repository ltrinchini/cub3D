# Cub3D

<div style="display" align="center">
	<img src="./rscs/cu3D.gif" width="42%">
</div>

## About

The project consists of creating a dynamic view in a maze using the ray-casting technique. To do this, I will use the school's proprietary minilibX graphics library to create real-time graphics.

Raycasting is a 3D rendering method used in first-person video games to simulate perspective and depth. It involves casting rays from the camera to determine which objects are visible on the screen and at what distance they are. This technique is also used for architectural simulation and 3D data visualization. The first game to use raycasting as a 3D rendering method is often considered to be "Wolfenstein 3D."

## Getting Started

To get started, clone the repository using the following command:
```bash
git clone git@github.com:ltrinchini/cub3D.git
cd cub3D
git submodule update --init libft
```

Then, compile the program by executing the following command:
```bash
make
```
## Creating a Map

Creating a map is an important part of the Cub3D project. To create a map, you must use a file in the *.cub format that contains the necessary information to generate the maze. The file must contain the following information:

- Screen resolution
- Path to the North texture
- Path to the South texture
- Path to the East texture
- Path to the West texture
- RGB color of the ceiling
- RGB color of the floor
- The map itself, represented by numbers corresponding to textures

## Usage

To run the program, use the following command:
```bash
./cub3D path_to_the_map
```

### Commands

|Commands|Functionality|
|-|-|
|ESC| Quit the program|
|← & → or a & d| Rotate the camera|
|↑ or w| Move forward|
|↓ or s| Move backward|

## Credit
This two-person project was done with [Martin ❤️ ](https://github.com/skippydgw42)
