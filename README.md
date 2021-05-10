# HotTapWelding_E2G

## General
* This directory consists of two files: a document briefly describing the modeling approach followed for the hot tap welding problem along with some additional questions related to it and a file containing the source code to run the simulation which will be discussed in detail next.

## Instructions to run the simualtion
* Download FreeFem from https://freefem.org and install.
* Change directory to **HotTapWelding_E2G** and run the simulation from terminal using the command `FreeFem++ HTWeld.edp`.
* This will generate an image showing the meshed domain for the problem.
* Press **return** or **Enter**, as prompted at the top of the image window. This will start an animation showing the contour plot for temperature distribution in and around the weld region through the entire duration of the simulation. Press **esc** as prompted at the top of the animation window.
* In the working directory, the individual contour plots for temperature distribution from the animation in the previous step will be saved as .**eps** files.
* The output generated will also have a .**dat** file consisiting of temperature values at a specific point (can be modified in the source code) in the geometry over the entire duration of the simulation.
