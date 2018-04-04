# Game Programming in C++ Code
This repository contains the source code for *Game Programming in C++* by Sanjay Madhav.

The source code for the chapters is released under the BSD 3-clause
license. See LICENSE for more detail. Note that this license does not apply to
the code in the External directory. Each External project is licensed separately.

# Building the Code
Each chapter's code is tested and works on both Microsoft Windows and Apple macOS.

To compile on Windows, install Microsoft Visual Studio 2017 Community
(https://www.visualstudio.com/downloads/). During installation, select the
"Game Development in C++" workflow. In each Chapter directory, there is a
corresponding ChapterXX-windows.sln file to open.

To compile on macOS, install Xcode from the App Store. Each chapter has
a corresponding ChapterXX-mac.xcodeproj file.

Code for Chapter 7 and beyond uses the FMOD API for audio. This requires
a separate installation from (https://www.fmod.com/download). Download
and install version 1.09.x of the FMOD Studio API (newer versions are untested).
On Windows, install FMOD to the default directory. On Mac, copy the contents
of the FMOD package into External/FMOD.

To compile on Linux, install g++ and download FMOD API and uncompress in this
same directory as this README.md.  Rename the directory created to fmodlinux 
Install the dependencis pkg-config GLEW, rapidjson, sdl2, sdl2_image, sdl2_ttf,
sdl2_mixer, and SOIL.  Then change in a Chapter directory you want to compile
and execute make.  For chapter07 and beyond. Use for x86_64 
$ export LD_LIBRARY_PATH=../fmodlinux/api/lowlevel/lib/x86_64:../fmodlinux/api/studio/lib/x86_64:$LD_LIBRARY_PATH
For Chapter08 you need to use a gamepad for input.

