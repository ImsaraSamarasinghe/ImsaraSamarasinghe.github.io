<style>
/* Dark mode CSS as the default styling */
/* Dark mode as default */
:root {
    --background-color: #121212; /* Dark background */
    --text-color: #e0e0e0; /* Light text color for body */
    --heading-color: #ffffff; /* White color for headings */
    --subheading-color: #b0b0b0; /* Light grey for subheadings */
    --button-background: #1b5e20; /* Dark green button background */
    --button-text-color: white; /* Button text color */
}

body {
    background-color: var(--background-color);
    color: var(--text-color);
    transition: background-color 0.3s, color 0.3s;
}

h1, h2, h3, h4, h5, h6 {
    color: var(--heading-color); /* White color for headings */
    margin-bottom: 10px;
}

h2 {
    color: var(--subheading-color); /* Lighter color for h2 */
}

a {
    color: #4CAF50; /* Green color for links */
    text-decoration: none;
}

a:hover {
    text-decoration: underline;
}

.hover-image {
  width: 150px; /* Set the desired size */
  transition: transform 0.3s ease, box-shadow 0.3s ease; /* Smooth transition */
}

.hover-image:hover {
  transform: scale(1.1); /* Scale the image */
  box-shadow: 0 4px 15px rgba(0, 0, 0, 0.3); /* Add shadow for depth */
}

.hover-project:hover {
  transform: scale(1.1); /* Scale the image */
  box-shadow: 0 4px 15px rgba(0, 0, 0, 0.3); /* Add shadow for depth */
}
    
.graph-container {
    text-align: center; /* Center the images */
}

.graph-row {
    display: flex; /* Use flexbox for the row */
    justify-content: center; /* Center the content in the row */
    margin-bottom: 20px; /* Space between rows */
}

.graph {
    width: 200px; /* Set a specific width for all images */
    height: auto; /* Maintain aspect ratio */
    margin: 0 10px; /* Add some space between images */
}

</style>


# About
<div style="text-align: center;">
  <a href="https://www.linkedin.com/in/imsaras/" target="_blank">
    <img src="GitHubProfile.jpg" alt="Imsara's Profile Picture" class="hover-image" />
  </a>
</div>

My name is Imsara Samarasinghe. I graduated with my MEng in Aeronautical Engineering from Imperial College London in 2024. During my time at university, I focused on the study of CFD and FE codes. I would like to further pursue this as a career in the future. I am currently looking for a role as a simulation engineer.

I have developed programming skills in Python, C++, Matlab and Fortran. I have written CFD codes that utilise MPI libraries to perform HPC-based fluid simulations. If you would like to see more of my projects download my CV in the link below.

[Download my CV](CV_Imsara_Samarasinghe.pdf)

---

# Master's Project
## Optimising 3D printed bone screws
This project implements a topology optimisation routine using the Finite Element Method (FEM) for a bone screw. The code leverages the Firedrake and IPOPT (via cyipopt) libraries to solve for the optimal material distribution of the screw material under a load, based on the Solid Isotropic Material with Penalization (SIMP) model. The output is the optimized material distribution and an animation of the optimization process.

The goal of this project was to design an internal structure for an orthopaedic screw that would prevent the bone-screw interface failure. The SIMP optimisation process produces a material distribution that reduces the shear stress concentration near the head of the screw, as this was reportedly the start of bone degradation. The resultant material distribution was also designed to be auxetic to prevent the screw from being pulled out due to shrinkage in tension.

<div style="text-align: center;">
  <a href="https://github.com/ImsaraSamarasinghe/Optimization-of-3D-Printed-Bone-Screws" target="_blank">
    <img src="screw.png" alt="Screw Design" class="hover-project" />
  </a>
</div>

---

# Coding Projects
## MPI Parallelised Lid Driven Cavity Flow
This project was undertaken as part of the 4th year HPC module. In this project, I used the MPI library and its functions to parallelise an existing C++ code. The project involved breaking the simulation domain into sevral subdomains. These subdomains were split among several processors and then functions such as `MPI_Send()` and `MPI_Recv()` were used for communication between processors. This was essential to facilitate the centred finite difference calculations at border nodes.

<div style="text-align: center;">
  <a href="https://github.com/ImsaraSamarasinghe/Lid-Driven-Cavity-Flow" target="_blank">
    <img src="Lid.png" alt="Lid Driven" class="hover-project" />
  </a>
</div>


## 2D FDTD simulation of Maxwell's Equations
This project simulates the propagation of an electromagnetic wave in 2D using the finite-difference time-domain (FDTD) method. It visualizes the evolution of the electric field over time in a grid, which is updated dynamically and saved as an animation. I created this project to learn how the leapfrog scheme is utilised to perform simulations of electromagnetic waves

<div style="text-align: center;">
  <a href="https://github.com/ImsaraSamarasinghe/2D-FDTD-Maxwells" target="_blank">
    <img src="wave_2d_Hy.gif" alt="Wave" class="hover-project" />
  </a>
</div>


## 2D Physics engine for multi-bodies
I created this code in Python using the Pygame library to develop my skills in Python programming and learn game development skills. I also wanted the oppurtunity to learn more about collision mechanics and how they are implemented.

<div style="text-align: center;">
  <a href="https://github.com/ImsaraSamarasinghe/Python-physics-engine" target="_blank">
    <img src="PhysicsEnginewithCollisionsUbuntu2024-09-2614-39-22-ezgif.com-video-to-gif-converter.gif" alt="Balls" class="hover-project" />
  </a>
</div>

## Agent based model for Viral Spread
I wrote this Matlab code as part of my first-year Computing and Numerical Methods assignment. I learnt how to create agent-based models, as well as implement fast and efficient array operations in Matlab. I scored a 22.5/25 for this project.

<div style="text-align: center;">
  <a href="https://github.com/ImsaraSamarasinghe/Agent-Based-model-for-Disease-Spread" target="_blank">
    <img src="2_Days.jpg" alt="Virus" class="hover-project" />
  </a>
</div>

## Agent based Schelling segregation model
<div style="text-align: center;">
  <a href="https://github.com/ImsaraSamarasinghe/Schelling-Segregation" target="_blank">
    <img src="" alt="Segragation" class="hover-project" />
  </a>
</div>
---

# Engineering Projects
## Simulation of aerofoil cross section using Xfoil and Star-ccm+
<div class="graph-container">
    <div class="graph-row">
        <img src="ClvA.png" alt="Graph 1" class="graph" />
        <img src="CdvA.png" alt="Graph 2" class="graph" />
    </div>
    <div class="graph-row">
        <img src="LDvA.png" alt="Graph 3" class="graph" />
    </div>
</div>

## High fidelity Simulation of aerofoil cross section in Nektar++
<div style="text-align: center;">
    <img src="3Daero.png" alt="3d aero" class="hover-project" />
</div>

## Finite element simulation of wing box torsion using Abaqus
<div style="text-align: center;">
    <img src="newBCtorsion.png" alt="torsion" class="hover-project" />
</div>

## Structural design of deployable re-entry vehicles and actuator sizing using SimScape
<div style="text-align: center;">
    <img src="IBeam-Static 3-Stress-Stress1.jpg" alt="I beam" class="hover-project" />
</div>
<div style="text-align: center;">
    <img src="MultiBody Pic Labelled.png" alt="linkage" class="hover-project" />
</div>

## PID controller design for a duo copter
<div style="text-align: center;">
    <img src="duoCop.png" alt="duoCopter" class="hover-project" />
</div>

## Wing box design for conceptual aircraft
<div style="text-align: center;">
    <img src="WingBoxDesign.png" alt="WingBox" class="hover-project" />
</div>
---
