
# Getting started with Pivot game engine

##  Requirements

* VulkanSDK 1.3.211
https://vulkan.lunarg.com/
* cmake >= 3.11
https://cmake.org/download/

###  - WINDOWS
* MSVC 17

### - LINUX
* GCC >= 11

##  Download

Download the engine here : https://github.com/EIP-Pivot/pivot/releases

### - WINDOWS

Download the .zip

### - LINUX

Download the .tar.gz or the AppImage

## Build and Compile

###  Build

* cmake -B build && cmake --build build --parallel 4

###  Compile

* cmake . -DCMAKE_EXPORT_COMPILE_COMMANDS=ON

## Lunch Editor

* cd build/
* ./editor/Debug/editor.exe

![enter image description here](https://cdn.discordapp.com/attachments/677099357173973014/995692249436393573/unknown.png)

**Go to our Quick start guide and start using Pivot now!**
