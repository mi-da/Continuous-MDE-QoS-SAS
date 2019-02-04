# Continuous Model-based Engineering of QoS-Aware Self-adaptive Systems
This page contains the architectural and simulation models to replicate the results of the paper: Continuous Model-based Engineering of QoS-Aware Self-adaptive Systems.

# Simulation Models
At the following [link](https://www.google.com) it is possible to download the simulation models. To run the co-simulation follow the following steps:

1. The downloaded folder contains the ITS workspace. Import the projects in the workspace as Eclipse Moven projects
2. The main file to run the experiments is: *se.mida.main.Main* in the project *MovsimYCalc*
3. In the program arguments you should indicate the number of vehicles per hour you want to experiment with (e.g., 1100)
4. The *conf* folder in *MovsimCosim* contains all the different configurations for the experimented scenarios. In the main file you must point to the configuration location you want to experiment with
5. All the results are presented after the end of the simulation


<p align="center">
  <img height="600" src='images/simulation.png'/>
</p>


