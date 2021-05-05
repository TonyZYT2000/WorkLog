# Simulation Environment

## Week 4, 5/2 - 5/8

- Design some classes for code reuse.
- Load general obj file. Test Stanford Bunny:
    | Ouline Mesh | Wireframe with Culling |
    | --- | --- |
    | ![](https://cdn.jsdelivr.net/gh/TonyZYT2000/ImageHost@master/BunnyOutline.png) | ![](https://cdn.jsdelivr.net/gh/TonyZYT2000/ImageHost@master/BunnyWire.png) |

## Week 3, 4/25 - 5/1

- Add a simple Phong lighting.
    ![](https://cdn.jsdelivr.net/gh/TonyZYT2000/ImageHost@master/Shading.png)

- Option to toggle wireframe display and culling (hide invisible components).
    | Wireframe | Wireframe with Culling |
    | --- | --- |
    | ![](https://cdn.jsdelivr.net/gh/TonyZYT2000/ImageHost@master/Wireframe.png) | ![](https://cdn.jsdelivr.net/gh/TonyZYT2000/ImageHost@master/Wireframe+Culling.png) |
    
- Outline the mesh.
    ![](https://cdn.jsdelivr.net/gh/TonyZYT2000/ImageHost@master/Outline-Wireframe.png)

## Week 2, 4/18 - 4/24

- Implement all 6 translational movement of the camera.
- Implement rotation of the camera, but the ground may get tilted. Not good.
- Add a land plane for better visual effect.
- Implement correct camera control on yaw and pitch same as in Blender.
    [![](http://img.youtube.com/vi/PwXRYMNXOtc/0.jpg)](https://www.youtube.com/watch?v=PwXRYMNXOtc "OpenGL + ImGui")

- Plan to start integrating Bryan's PBD solver.

## Week 1, 4/11 - 4/17

- Learn [CMake](https://cmake.org/) building system and [Conan](https://conan.io/) package manager.
- Setup project using OpenGL and [Dear ImGui](https://github.com/ocornut/imgui).
    ![](https://cdn.jsdelivr.net/gh/TonyZYT2000/ImageHost@master/DearImGui.png)

- Render a basic spinning cube.
    ![](https://cdn.jsdelivr.net/gh/TonyZYT2000/ImageHost@master/SpinningCube.png)

- Test project compatibility on Ubuntu. Successfully build and run on Ubuntu.
- Add some camera control. To be continued.
