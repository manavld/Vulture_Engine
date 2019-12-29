# Vulture Engine

Vulture Engine is a 3D Game Engine developed for a university project in CITM UPC (Terrasa, Spain) in our degree in Videogame Developement and Design.

## Authors

* José Rodríguez: [https://github.com/joserm45](https://github.com/joserm45)

* Manav Lakhwani: [https://github.com/manavld](https://github.com/manavld)

## Instructions

Download the .zip in the last release in [https://github.com/joserm45/VultureEngine/releases](https://github.com/joserm45/VultureEngine/releases) and open the file .exe to use the game engine.

## Github Repository

[https://github.com/joserm45/VultureEngine](https://github.com/joserm45/VultureEngine)

## Game Engine Screenshot

<img src="ScreenShot.jpg" alt="ScreenShot">

# Systems

## Hierarchy

<img src="Hierarchy.jpg" alt="Hierarchy">

## Inspector

<img src="Inspector.jpg" alt="Inspector">

## Optimization

Quadtree: With Static Game Object check box
Camera Culling: hide Game Objects that are not in Main Camera

## Mouse Pickying

With mouse we can select and did focus to Game Object on the scene

## Engine State

We can Start/Pause/Stop Engine and be the main camera

<img src="State.jpg" alt="State">

## Bounding Box

We use AABB to encapsulate meshes and discarded using frustum culling in editor mode and mouse picking enabled to select game object on scene

## Configuration

<img src="Configuration.jpg" alt="Configuration">

## Console

<img src="Console.jpg" alt="Console">

# Controls

* WASD: Camera Movement
* Right Click: Rotate Camera
* Shift: Duplicate Speed Movement
* Mouse Wheel: Zoom in and out
* F: Focus Camera to Gameobject
* Alt+Left Click: Rotate around Gameobject
* Drag&Drop: Drag any model or texture to apply to scene

## Tools Used

* Visual Studio 2017: [https://visualstudio.microsoft.com/es/downloads/](https://visualstudio.microsoft.com/es/downloads/)
* ImGui 1.51: [https://github.com/ocornut/imgui](https://github.com/ocornut/imgui)
* SDL 2.0.6: [https://www.libsdl.org/](https://www.libsdl.org/)
* Glew 2.0.0: [http://glew.sourceforge.net/](http://glew.sourceforge.net/)
* MathGeoLib 1.5: [https://github.com/juj/MathGeoLib](https://github.com/juj/MathGeoLib)
* OpenGL 3.1: [https://www.opengl.org/?](https://www.opengl.org/?)
* Assimp 4.1.0: [http://www.assimp.org/index.php/downloads](http://www.assimp.org/index.php/downloads)
* DevIL 1.8.0: [http://openil.sourceforge.net/download.php](http://openil.sourceforge.net/download.php)
* Par Shapes: [https://github.com/prideout/par](https://github.com/prideout/par)

## License

We use the MIT License this is a permissive free software license originating at the Massachusetts Institute of Technology.

MIT License

Copyright (c) 2019 Jose Rodriguez & Manav Lakhwani

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
