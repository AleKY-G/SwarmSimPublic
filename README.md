# SwarmSim

This project implements the algorithms described in [Giusti2022].

Simulate swarms of planar mobile agents with first order dynamics and implement distributed control laws to obtain geometric lattice formation.

To execute your first simulation simply run Launcher.m.

Features:
  - Simulation of swarms of planar mobile agents with first order dynamics.
  - Distributed control laws to obtain geometric lattice formation.
  - Acquisition of metrics to evaluate the performance.
  - Adaptive tuning of the control gains.
  - Embedded options to test agents failure, dynamic lattice reconfiguration and actuation noise.
  - Extensive simulations to tune the control gains (see BruteForceTuning.m).
  - Extensive simulations to study the effects of the parameters (see StabilityAnalysis and SequentialLauncher.m).
  - Local stability analysis through linearization (see crystalStabilityMulti).
  - Interface with Robotarium code to perform advanced simulations and real life experiments (see RobotariumSimulator). 
    For more details and to use the Robotarium refer to https://www.robotarium.gatech.edu.
  - Plot functions to visualise the results.

Copyrights: If you use this code for research purposes and want to mention it in one of your publications, please cite [Giusti2022].

In the Media folder, there is a video supplement for [Giusti2022].

Authors: Andrea Giusti and Gian Carlo Maffettone.
Date: 2022

[Giusti2022] Giusti, A., Maffettone, G. C., Fiore, D., Coraggio, M., & di Bernardo, M. (2022). Distributed control for geometric pattern formation of large-scale multirobot systems. arXiv preprint arXiv:2207.14567.
