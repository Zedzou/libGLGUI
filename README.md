# libGLGUI

用Dear ImGui和OpenGL编写的渲染器

## 目录结构
```
libGLGUI
|---README.md
|---CMakeLists.txt
|---main.cpp
|---cmake
    |---Findgl3w.cmake // 依赖gl3w扩展库
    |---UseImGUI.cmake // 依赖ImGUI扩展库
|---ImGuiExtension
    |---CMakeLists.txt
    |---include
        |---ImGuiExtension
            |---LocalFileSystem.h // ImGui浏览打开文件控件demo
            |---tinyfiledialogs.h
    |---source
        |---LocalFileSystem.cpp
        |---tinyfiledialogs.cpp
|---libGUI
    |---CMakeLists.txt
    |---GUI.h
    |---GUI.cpp
    |---test // 用于测试libGUI
        |---test.cpp
        |---CMakeLists.txt
```
    
## Build
```
mkdir build && cd build && cmake .. && make
```
