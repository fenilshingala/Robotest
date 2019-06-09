# Game Robotest

### Requirements:
  * OS: Windows.
  * IDE: Microsoft Visual Studio.
#### You may have to change Windows SDK version. Project is using version 10.0.17134.0
#### Game can have lower frame rate in lower config GPUs.
###
### Game engine(FlyEngine):
#### Core:
  * Programming language: C++
  * Engine architecture: Entity Component System
  * Type Reflection: [rttr](https://www.rttr.org/) library
  * Serialization: JSON ([rapidjson](http://rapidjson.org/))
  * UI: [ImGui](https://github.com/ocornut/imgui)
  * Window Manager: [glfw](https://www.glfw.org/)
  * Scripting: [Lua](https://github.com/ThePhD/sol2)
  * Logging: [spdlog](https://github.com/gabime/spdlog)
  * Memory Leak Detection: [VLD](https://kinddragon.github.io/vld/)
#### Graphics:
  * Graphics API: OpenGL 4.3
  * 3D Model loading: [assimp](http://www.assimp.org/)
  * Text: [freetype](https://www.freetype.org/)
  * Gl Loader-Generator: [glad](https://glad.dav1d.de/)
  * Image loader: [stb_image](https://github.com/nothings/stb)
#### Other
  * Math library: [glm](https://glm.g-truc.net/)
  * Audio engine: [fmod](https://www.fmod.com/)
  * Interpolation of variables: [tweeny](https://github.com/mobius3/tweeny)
  * File System: [dirent](https://github.com/tronkko/dirent)
###
### Project was made while I was studying in DigiPen Institute of Technology
### Team name: fireflies
Team member | Role
------------ | -----
Myself             |  Engine and Gameplay Logic
Dhrumil Shukla     |  Engine and Gameplay Logic
Arnold George      |  Graphics
Shashwat Pandey    |  Physics
Ivan Cazares Lopez |  Audio and Game Design
