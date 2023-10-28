# Tutorial

This tutorial isn't meant to explain how to run nor does it explain how to operate any of the tools I might end up developing. This tutorial is meant as a refresher for me in case I ever forget anything.

To run Raylib on Linux (more details in [Raylib's Wiki](https://github.com/raysan5/raylib/wiki/Working-on-GNU-Linux)) you first need GCC (to compile C/C++), you need make to compile Raylib and git to get the latest version of it's source code, makefiles are already attached to raylib. You might also need CMake (install anyway). You then need to install some required libraries for audio, accelerated graphics, and for your windowing system. More information in [Raylib's Wiki](https://github.com/raysan5/raylib/wiki/Working-on-GNU-Linux).

Wayland requrest some manual intervention to support GLFW.

I prefer using a dynamic shared version, more details in [Raylib's Wiki](https://github.com/raysan5/raylib/wiki/Working-on-GNU-Linux).

To uninstall use
`sudo make uninstall RAYLIB_LIBTYPE=SHARED`

to build use
`make PLATFORM=PLATFORM_DESKTOP RAYLIB_LIBTYPE=SHARED`
