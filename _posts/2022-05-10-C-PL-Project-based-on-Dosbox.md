---
permalink: /posts/CPLP

---

# Class Project of C Programming Language

This is a emulator of USV developed in C in Borland C++ 3.1 installed in Dosbox, which is a really weird environment to work with :).
The github repository is [here](https://github.com/101010zyl/usv).

## Introduction
The goal of the program is to emulate the movement of unmanned surface vehicle in a lake. 
The program is developed completely in C, compiled and run in Borland C++ 3.1, and the graphics are developed using the libraries in Dosbox. 

## Develop Process
To emulate the movement of the USV, 
we employ A* algorithm to find the shortest path from the starting point to the destination
and Dijkstra algorithm to find optimal order of the points to visit.
<img src="{{ "/assets/images/CPLP-debug.gif" | absolute_url }}">
The USV is represented by a small boat, and the lake is represented by a 2D array. 

## Final Result
We can slect multiple point in the lake,
and the program will find the shortest path and display the movement of the USV.
![Final](/assets/images/CPLP-final.gif)