# Trengine
## Build Trengine Solution Using Premake 
- Rename premake5-GLFW.lua to "premake5.lua", and put in vendor/GLFW, with GLFW as a submodule
- Rename premake5-GLAD.lua to "premake5.lua", and put in vendor/GLAD, with GLAD as a submodule
- Rename premake5-ImGui.lua to "premake5.lua", and put in vendor/imgui, with imgui as a submodule
- Paste imgui_impl_glfw.cpp in vendor/imgui/backends from sln
- Paste imgui_impl_opengl3.cpp in vendor/imgui/backends from sln
- Paste imgui.cpp in vendor/imgui from sln
=> Double click GenerateProject.bat to buid the solution
