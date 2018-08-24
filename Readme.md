# Documentation
2D_soft_core.f simulates active particles confined in a box with periodic boundary conditions. The particles are submitted to a Brownian motion and interact via a repulsive soft-core and Vicsek-like interactions. This particular code is designed to study the evolution of the system, so it generates .dat files containing the state of the system for different times.

The functions of My_script are:
*Compile and execute FORTRAN program
*Create .png images from .dat files (using either Python or Gnuplot). 
*Join together the .png images to create a .mp4 video
*Erase .png and .dat files of folder

WARNING: in the actual state of the scripts, the .png images shows the state of the system and an inpset with the radial distribution function. There is a bug on the Gnuplot code, so videos with inset plots can only be generated by using python.

All the codes are carefully described with comments, please contact jvfglrschz@gmail.com for doubts.
# URL
* https://www.youtube.com/watch?v=j4bS2HwzLqU. 2D Active Cluster Crystals.
