# Introduction

Simple DirectMedia Layer.

<https://en.wikipedia.org/wiki/Simple_DirectMedia_Layer>

<https://www.libsdl.org/>

Cross platform library for user input (mouse, keyboard, touch), graphics, sound, haptics. Basically a huge wrapper on top of tons of incompatible APIs.

There is some support for hardware acceleration it seems: <https://www.libsdl.org/release/SDL-1.2.15/docs/html/guidevideoopengl.html>

Started by venerable Loki software <https://en.wikipedia.org/wiki/Loki_Software>

Widely cross platform: Windows, Mac, Linux, Android, [iOS](http://stackoverflow.com/questions/23063659/porting-sdl-app-to-ios).

Widely popular. Steam for Linux embeds it, and the lead dev is working for them as of 2016. 2014 Steam talk <https://www.youtube.com/watch?v=MeMPCSqQ-34>

## Build

    hg clone http://hg.libsdl.org/SDL
    mkdir -p build && cd build && cmake .. && cmake --build .

Run examples: you must first install it (or checkout to the same version as that installed by your package manager). Then:

    cd test
    ./configure
    make
