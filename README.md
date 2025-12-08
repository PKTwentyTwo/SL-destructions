# SL-destructions
## Overview
This is a collection of glider destructions in Conway's Game of Life. Glider destruction refers to colliding one or more gliders with a pattern to leave nothing except for vacuum.
A number of unsolved issues relating to glider destruction exist, but the one I am most interested in is the smallest still life (stable pattern that never changes between generations) that cannot be destroyed with 2 gliders.
As I have found existence proof the easiest way to tackle this problem, I have found many destructions using a custom Python script, but then I need to provide all of the destructions as proof, which can take many megabytes for larger SL.
## Format
This repository stores my destructions in a compressed format using 7-Zip. 7-Zip is an efficient open-source file archiver licensed under the GPL, and it can be downloaded from https://www.7-zip.org.
The name of each archive is based on the equivalent tabulation for Catagolue - xs19.7z stores destructions for 19-bit still lifes, for example.
Tabulations xs4 through xs18 are all in the same archive, as they are small - when compressed, the total size is <1MB.
## Current progress
Currently, it has been determined that the lower bound for the smallest SL resilient enough to resist 2 gliders is 22 cells.
