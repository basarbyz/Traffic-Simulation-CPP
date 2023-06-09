# Project Description
During the internship, all essential elements of object-oriented software development and their implementation in the C++ language, using modern smart pointer concepts, was practiced and applied to a simplified example. The classes of the Standard Template Library (STL) was introduced and used to represent commonly used data structures such as vectors, lists, or associative memories.

The task consists of subtasks that build upon each other, eventually leading to the complete solution. The individual tasks are grouped into two blocks, with each block requiring a separate project to be created using Eclipse. Each block was also be tested and require a separate assessment. The goal is to implement the tasks in such a way that a test program from Block 1 will still function at the end of the internship.

# Objective
The objective is to model and simulate traffic on roads in an underdeveloped area. Various types of vehicles, such as cars and bicycles, was released from a starting point (intersection) at individual start times. Each vehicle has both a time and distance counter for the total distance as well as the distance traveled on the current path. The simulation is set up with three simulation objects: vehicles, paths, and intersections. A connection between two intersections is realized through a road consisting of two opposite paths (outbound and return). Each path manages the vehicles on it, and each intersection manages the paths originating from that intersection. Paths can accommodate both moving and parked vehicles. When the simulation reaches the parking time of a parked vehicle, it will be turned into a moving vehicle.

All simulation objects contain a function that performs a simulation step. Intersections simulate the paths originating from them, and paths simulate the vehicles on them. Each time step involves the simulation of all intersections in the system in sequence, followed by the simulation of all other simulation objects. The system is controlled by a global clock that will synchronize the simulation of all objects. Speed limits may apply on some paths due to their nature (e.g., city streets, highways).

![imageedit_2_7808276905](https://user-images.githubusercontent.com/65845672/230884361-1f974cb8-8a03-46ad-9c7b-ed5d04d87bcb.png)


     
