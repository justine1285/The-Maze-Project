# The Maze
The Maze is a 3D Maze game that uses raycasting to render a 2D map into a 3D navigable world!

The Maze was written in C using SDL2 library. Development was performed using Ubuntu 14.04 LTS, using gcc (Ubuntu 4.8.4-2ubuntu1~14.04) 4.8.4.

### About SDL2

Simple DirectMedia Layer is a cross-platform development library designed to provide low level access to audio, keyboard, mouse, joystick, and graphics hardware via OpenGL and Direct3D. It is used by video playback software, emulators, and popular games including Valve's award winning catalog and many Humble Bundle games.

## Installation
```sh
$ git clone https://github.com/justine1285/The-Maze-Project.git
```

#### Controls
- `W` : move forward
- `S` : move backward
- `D` : rotate camera right
- `A` : rotate camera left
- `E` : strafe right
- `Q` : strafe left
- `F` : toggle fullscreen
- `ESC` : quit

### Technologies Used and Choices
In my maze game project, I carefully selected technologies to fulfill specific requirements and align with our development goals. Here is an overview of the technologies used and the reasoning behind our choices:
Technologies Used and Choices Made: In our maze game project, we carefully selected technologies to fulfill specific requirements and align with our development goals. Here is an overview of the technologies used and the reasoning behind our choices:

1. SDL2 (Simple DirectMedia Layer):
I chose SDL2 as the primary library for game development due to its cross-platform compatibility and extensive functionality.
SDL2 provided me with low-level access to graphics, audio, and input handling, allowing me to create an immersive and interactive game experience.
By working directly with SDL2, I had greater control over the game's performance and customization options.

2. Raycasting:
I implemented raycasting as the rendering technique for creating a 3D-like representation of the maze on a 2D screen.
Raycasting allowed me to achieve a pseudo-3D effect, giving depth and perspective to the maze environment.
This technique, popularized by early first-person shooter games, provided an efficient and visually compelling way to render the maze and optimize performance.

3. C Programming Language:
I chose C as the primary programming language for its efficiency, performance, and ability to work seamlessly with SDL2.
C allowed me to take full advantage of hardware acceleration and optimize the game's rendering and processing capabilities.
Additionally, C provided the necessary flexibility for memory management and control over resources, critical for game development.

## Compilation
```sh
$ gcc -Wall -Werror -Wextra -pedantic ./src/*.c -lm -o maze `sdl2-config --cflags` `sdl2-config --libs`;
```

## Flowchart
![The Maze Flow Chart](https://drive.google.com/file/d/1WktQD7kdYC3XM2i-VYpDTj1uewsUwcRk/view?usp=sharing)

### Authors/Developers
- Adugbo Mamuyovwi Justine
- Olatomide Iyanu Israel

### socials:
- [GitHub](https://github.com/justine1285)
- [linkdin](https://www.linkedin.com/in/adugbo-Justine-b83106176)
- [Twitter](https://twitter.com/justine_mamus)

- [GitHub](https://github.com/Oiyanu)
- [linkdin](https://www.linkedin.com/in/iyanu-olatomide-214b70283)
- [Twitter](https://twitter.com/OlatomideI)

### Resources
- [SDL2 API](https://wiki.libsdl.org/CategoryAPI)
- [LazyFoo Beginning Game Programming](http://lazyfoo.net/tutorials/SDL/index.php)
- [Ray-Casting Tutorial For Game Development And Other Purposes by F. Permadi](http://permadi.com/1996/05/ray-casting-tutorial-table-of-contents/)
- [LodeV Raycasting Tutorial](http://lodev.org/cgtutor/raycasting.html)
- [Game Engine Black Book](https://www.amazon.com/Game-Engine-Black-Book-Wolfenstein/dp/1539692876)
- [John Watson](https://www.youtube.com/@johnwatson2675/streams)
