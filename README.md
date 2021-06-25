# The Caterpillar


-------------- Files --------------

The project contains a single source file:
- Omida.cpp

This file contains the implementation of the simulation of a caterpillar in 3D space.


--------------Dependencies--------------

In order for the project to run, it needs a few
files (libraries) that can be downloaded from the following link:
- http://www.mediafire.com/file/cmlnr0pj0pyha5d/Glew_and_Glut.zip/file


-------------- Running & Installing --------------

The project can be opened in the program in which it was implemented:
- Visual Studio 2019

Before being run, the following must be completed (if any)
create a new project):
- Right-Click on Project -> Properties
- C / C ++ -> General -> Additional Include Directories -> Edit -> Must
added both folders / includes from each directory (freeglut and glew-1.11.0)
- Linker -> General -> Additional Library Directories -> Edit -> Must
added both / lib folders from each directory (freeglut and glew-1.11.0)
- Linker -> Input -> Additional Dependencies -> Edit -> The name must be entered
libraries, more precisely: freeglut.lib and glew32.lib
- The freeglut.dll and glew32.dll files must be copied to the directory
project

If you are unsure, you can watch the following video:
- https://www.youtube.com/watch?v=8p76pJsUP44&ab_channel=ProgrammingKnowledge


--------------Orders--------------

- W, A, S, D -> rotating the caterpillar in space
- directional arrows -> movement of the caterpillar in space
- left click and right click on / off two types of lights
