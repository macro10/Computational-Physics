# Computational-Physics
This repository contains all of the projects I worked on during the spring semester of 2022 at High Point University in Computational Physics. PHY 2200 is a project-based introduction to computational physics through computational modeling that is taught by Dr. Titus. Throughout the class I learned to construct, solve, validate, and communicate mathematical models of physical systems. In my projects, I explored topics such as particle distribution, modelling motion with ODE integration, radial oscillations, curve fitting, and modelling standing wave oscillations.

[Project 0: ](https://github.com/macro10/Computational-Physics/blob/4a2904dbd08a0ceac870a79ca27b6ad94164e08f/Particle-Distribution-Filter.ipynb) Particle Distribution of Water Inside a Filter

In this project, I modelled a collection of particles that are being thrown in the negative y direction. The particles are directed into a lattice of rods representing a filter. The goal of this project was to measure the distribution of particles through the filter based on the distance between each rod and how large the radius of the particles are.

[Project 1:](https://github.com/macro10/Computational-Physics/blob/f479f693ecdb9b796e0a38a136fbf82aa1a32a12/Modelling-Rocket-Motion-Using-ODE-Integration.ipynb) Modelling Rocket Motion Using ODE Integration

This simulation modelled the motion of a rocket with changing mass due to burning fuel. My partner and I used reasonable values for initial mass, fuel burn rate, and exhaust velocity to model the rocket's position, velocity, mass, and momentum versus time. We modelled a rocket with one fuel tank as well as a rocket with two fuel tanks with fuel jettisons after 30% of the fuel is burned. The goal of the project was to conclude which rocket would have a greater final velocity and momentum.

[Project 2:](https://github.com/macro10/Computational-Physics/blob/f479f693ecdb9b796e0a38a136fbf82aa1a32a12/Rocket-Engine-Curve-Fitting.ipynb) Using Curve Fitting to Plot the Motion of a Model Rocket

In this project, I used thrust data of a C6-5 model rocket to create a curve fit and make a function. Next, I used the function to plot the motion of the model rocket and find its peak altitude. The parameters of the function I used were borrowed from [an article by physicist Thomas A. Dooling](https://aapt.scitation.org/doi/10.1119/1.2731273). The purpose of this project was to become confortable with curve fitting, as I had not dealt with it in any of my other classes yet.

[Project 3:](https://github.com/macro10/Computational-Physics/blob/4f141d8bcfcc346931b79637e6b7dfc2805a094b/Radial-Oscillation.ipynb) Creating a Radially Oscillating Circle

This project used a system of oscillating "balls and springs" to represent atoms oscillating in a ring formation. Throughout the semester, we explored how to make linear oscillations, but Kolt and I wanted to attempt to make a circular one. We used a function to create eigenvectors and calculate the displacement of the atoms in the ring. This project became the precursor for our semester project, where we expounded on radial oscillations and refined our mathematical framework.

[Semester Project:](https://github.com/macro10/Computational-Physics/blob/4f141d8bcfcc346931b79637e6b7dfc2805a094b/Semester-Project-Circular-Standing-Waves.ipynb) Modeling Circular Standing Waves

For our semester project we chose to model circular standing waves. We used the same ball and spring model as the previous project. A standing wave is a vibration of a system in which some particular points remain fixed while others between them vibrate with the maximum amplitude. The goal of this project was to simulate a real circular standing wave, just like the one shown in [this](https://youtu.be/df3oJPi9_mg?t=66) video.
