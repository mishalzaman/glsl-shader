# GLSL Shader Tool

A simple tool to create and edit vertex and fragment shaders.

## Dependencies
OpenGL 3 - 4
GLFW
[gla](https://glad.dav1d.de/) (Maybe swtich this for a different extension library?)
[imgui](https://github.com/ocornut/imgui)

## Features
- [ ] Mesh upload
  - [ ] .obj
  >> We can keep it simple by just allowing obj files as the main focus of this application is to create / edit shader files.
- [ ] Create / edit vertex shader
- [ ] Create / edit fragment shader
- [ ] Realtime compilation of shaders
>> This is possible considering the fact that shader files a C string files which can be re-compiled and linked.
- [ ] Syntax highlight
- [ ] Code validation
