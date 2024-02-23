<p align="center">
 <img width="8%" alt="star" src="https://github.com/irulanCorrino/quel-solaar/assets/98284211/aa21950f-66f4-4a56-bd04-af8a2cb4677d"> <ins>love toolkit</ins>
</p>

A wiki for this repository mirrors original [website](https://gamepipeline.org/)[^1], which is documenting[^2] all the libraries developed by Eskil Steenberg under the Quel Solaar banner. All source code is available under the Free BSD license meaning that you are free to use it anyway you want as long as you attribute its source.

All code can be downloaded [HERE](http://www.quelsolaar.com/quel_solaar.zip)

> The libraries here comprise a significant amount of functionality that has been written to be easy to use, light weight, have few dependencies. I'm releasing this software because i hope that it can help other developers to make games and other software. The code is divided into a number of libraries and you can just include them into your project once you need. I will do my best to answer any question you may have on eskil 'at' obsession dot se.
---
### Forge

Basic definitions for [types](https://en.wikipedia.org/wiki/Data_type) and [constants](https://en.wikipedia.org/wiki/Constant_(computer_programming)), [memory debugging](https://en.wikipedia.org/wiki/Memory_debugger), [vector](https://en.wikipedia.org/wiki/Euclidean_vector) and [matrix](https://en.wikipedia.org/wiki/Matrix_(mathematics)) math, [sort](https://en.wikipedia.org/wiki/Sorting_algorithm), [color space conversion](https://en.wikipedia.org/wiki/Color_space#Conversion), [random number generation](https://en.wikipedia.org/wiki/Random_number_generation) and [Perlin noise](https://en.wikipedia.org/wiki/Perlin_noise), curves and animation.

### Imagine

Platform layer for multithreading, dynamic library loading, directory traversal, and XML based settings storage system.

### Betray

Extensive platform layer that lets you open windows, read input and connect to mics and speakers. Betray has an extensive plugin system that makes all applications written for betray support hardwars such as [3D sound stereoscopics](https://en.wikipedia.org/wiki/3D_audio_effect), multi-touch, [color correction](https://en.wikipedia.org/wiki/Color_grading#Hardware), motion sensors, headmounted displays and more.

### Relinquish

A lightweight convenience wrapper around OpenGL and OpenGL ES (Code written for Relinquish runs on both), with shaders, textures, vertex arrays and FBOs. Relinquish wraps many of newer fetures of OpenGL so that code will take advantage of them if they are available.

### Testify

Library for encoding/decoding binary file or network data, with a extensive [debugging](https://en.wikipedia.org/wiki/Type_system#Type_checking) and [error](https://en.wikipedia.org/wiki/Byzantine_fault) [checking system](https://en.wikipedia.org/wiki/Data_validation). Manages little/big [endianness](https://en.wikipedia.org/wiki/Endianness)

### Seduce

Fully scalable 3D [GUI toolkit](https://en.wikipedia.org/wiki/Widget_toolkit) with buttons, text rendering and editing, manipulators, camera controls, popups, sliders, panels, translation and hit-detection. All controlable with mouse and keyboard, touch or game controller. Seduce is not yet fully documented.

Here is a video of some of the features of the platform layer Betray | Here is a video showing off the Seduce UI toolkit
:-: | :-:
[<img src="https://img.youtube.com/vi/oMJP6vlsmbE/maxresdefault.jpg" width="100%">](https://www.youtube.com/watch?v=oMJP6vlsmbE) | [<img src="https://img.youtube.com/vi/oDulGQnjsDQ/maxresdefault.jpg" width="100%">](https://www.youtube.com/watch?v=oDulGQnjsDQ)

> It's important to note that the goal of Quel Solaar is to develop real world software and not middleware. These libraries are a by-product of development rather than the goal itself. Having said that, all these libraries have been tested in released software, and almost all of them have been broken out of software in order to be reused. Since LOVE's development winddown in 2012, all this libraries have been refactored, rewritten. I consider all libraries here to be very well designed and future looking, and i do not expect major refactoring.

[^1]: This website is currently under a construction as i spend an hour each day working through the documentation. More is to come....

[^2]: This entire website was generated using the DocGen tool.
