# final-project_mms
# Using molecular simulations to study formation of liquid crystal nanodroplets from a solution

# Table of Contents
  CONTENTS OF THIS FILE
  ---------------------
  * Introduction 
  * Requirements
  
  INTRODUCTION
  ------------

  Lammps input files are included in this repository in order to perform molecular dynamics 
  simulations involving Gay-Berne ellipsoids in a Lennard-Jones fluid. 
  In this work, the goal is to present a computer simulation of the separation of nematic 
  nanodroplets from a homogeneous binary solution.1 The liquid crystal particles are 
  represented by elongated ellipsoidal GB mesogens and the solvent is modeled by spherical 
  LJ particles.

  The simulations in this report were for systems of 1000 and 5000 total particles. 
  All initial configurations have been prepared by first running NPT and after this 
  occurs a NVE simulation is performed.

  REQUIREMENTS
  -------------
  * LAMMPS input file with the desired configurations. 
  * .sh file to submit job for the simulation. 
