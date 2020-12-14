# Methanol-Molecular-Dynamics

This repository contains all the files required for performing molecular dynamics simulation of Methanol. Each simulation was carried out in the **isothermal isobaric ensemble**. This repo contains three subdirectories for the three different NPT simulations, the conditions for which are descibed as follows- 

300K & 1atm\
320K & 1atm\
300K & 250atm

Each sudirectory contains the `LAMMPS` script for running the simualtion and the corresponding `.pdb` topology files. A `.log` file is generated on completion of the simulation.

Extensive equilibriation was carried out for 1 ns. The simulation data after 1 ns was used for analysis and calulation of time-average thermodynamic properties and response functions. 
The results were analysed using the `lammps_logfile` package in Python. The Jupyter notebook used for analysis is included.
