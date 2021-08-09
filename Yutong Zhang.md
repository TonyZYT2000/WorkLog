# Simulation Environment

## Week 17, 8/1 - 8/7
- Build VIPER on Ubuntu with CUDA support.
- Read VIPER's shader codes and migrates some effects.
- Improve visualization of Entong's sphere data.
    | Solid Meshes | Meshes with Outlines | Solid Spheres with Wire Rods |
    | --- | --- | --- |
    | ![](https://cdn.jsdelivr.net/gh/TonyZYT2000/ImageHost@master/Rod1.png) | ![](https://cdn.jsdelivr.net/gh/TonyZYT2000/ImageHost@master/Rod2.png) | ![](https://cdn.jsdelivr.net/gh/TonyZYT2000/ImageHost@master/Rod3.png) |

- Improve code structure and GUI interface.
    
    ![](https://cdn.jsdelivr.net/gh/TonyZYT2000/ImageHost@master/GUI.png)

## Week 16, 7/25 - 7/31
- Write a TF broadcaster.
- Modify the main program to be a ROS node.
- Create classes for Box, Sphere and Cylinder.
- Create URDFObject class that reads URDF model and listens to TF.
- Need correct transformation between ROS coord and OpenGL coord.

## Week 12 13 14 15, 6/27 - 7/24
- Learn ROS tutorials.
- Learn TF tutorials.
- Learn URDF tutorials.
- Visualize Entong's sphere data.

## Week 11, 6/20 - 6/26
- Design classes correponding to robot Link and Joint.
- Parsing URDF:
    | Links Data | Joints Data |
    | --- | --- |
    | ![](https://cdn.jsdelivr.net/gh/TonyZYT2000/ImageHost@master/LinksData.png) | ![](https://cdn.jsdelivr.net/gh/TonyZYT2000/ImageHost@master/JointsData.png) |

## Week 9 10, 6/6 - 6/19
- Final week and travel.

## Week 8, 5/30 - 6/5
- Robot arm hierarchy.

## Week 7, 5/23 - 5/29
- Reduce warnings and debug for potential errors.
- Make the code compatible on Linux.

## Week 6, 5/16 - 5/22
- Nothing :-\( \(busy week for midterms and homework\).

## Week 5, 5/9 - 5/15

- Add libigl into the project.
- Use libigl libraries to handle mesh processing:
    | Without libigl, Full-Resolution Rabit | With libigl, Rabit with Reduced Faces |
    | --- | --- |
    | ![](https://cdn.jsdelivr.net/gh/TonyZYT2000/ImageHost@master/Rabit-Full.png) | ![](https://cdn.jsdelivr.net/gh/TonyZYT2000/ImageHost@master/Rabit-Decimate.png) |
- Improved POV-Ray lighting
    | Front View | Back View |
    | --- | --- |
    | ![](https://cdn.jsdelivr.net/gh/TonyZYT2000/ImageHost@master/POV-Ray1.png) | ![](https://cdn.jsdelivr.net/gh/TonyZYT2000/ImageHost@master/POV-Ray2.png) |
- Start combining with Bryan's solver.

## Week 4, 5/2 - 5/8
- Design some classes for code reuse.
- Load general obj file. Test Stanford Bunny:
    | Ouline Mesh | Wireframe with Culling |
    | --- | --- |
    | ![](https://cdn.jsdelivr.net/gh/TonyZYT2000/ImageHost@master/BunnyOutline.png) | ![](https://cdn.jsdelivr.net/gh/TonyZYT2000/ImageHost@master/BunnyWire.png) |
    
- Export to POV-Ray scene file and render:
    | Export Button | Render from Exported File |
    | --- | --- |
    | ![](https://cdn.jsdelivr.net/gh/TonyZYT2000/ImageHost@master/POVRay-Export.png) | ![](https://cdn.jsdelivr.net/gh/TonyZYT2000/ImageHost@master/POVRay-Render.png) |

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
