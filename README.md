<style>
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

The goal of this project was to design an internal structure for an orthopaedic screw that would prevent the bone-screw interface failure. The SIMP optimisation process produces a material distribution that reduces the shear stress concentration near the head of the screw, as this was reportedly the start of bone degradation. The resultant material distribution was also designed to be auxetic to prevent the screw being pulled out due to shrinkage in tension.

Access my project repository [here](https://github.com/ImsaraSamarasinghe/Optimization-of-3D-Printed-Bone-Screws).

<div style="text-align: center;">
  <img src="screw.png" alt="Screw Design" class="hover-project" />
</div>

---

# Coding Projects
## 2D FDTD simulation of Maxwell's Equations
## 2D Physics engine for multi-bodies

---

# Engineering Projects
## Simulation of aerofoil cross section using xfoil and Star-ccm+
