# MasterThesis_DMF
Master thesis - Simulation Models of Dual Mass Flywheel

In this respitory you will find models used in Master thesis - Simulation Models of Dual Mass Flywheel, (c) Daniel Johansson, Kim Karlsson. 

Under AVL.rar:
  - Model 1, Linear Spring System
  - Model 2, Two Stage Spring System
  - Model 3, Arc-Spring Friction Model
  - Load data (Sine and realistic), Fricion data tables

Under PYTHON.rar:

In the folder, Linear and Two stage system, all the scripts and data to compute the results for Model 1,2 are 
included.
  - The script FlywheelTorque3.py was used to plot the more "realistic" torque for 2 revolutions of the crankshaft.
  - The main script LinearTwostageSpringSystem.py was used for the simulations for Model 1,2 by changing the input to the one of interest.

The folder, Model 3 Friction Model, includes all the scripts for model 3, the frictional model. The main script Model3FrictionModel.py was used to simulate the response of the DMF including friction, these results were compared and verifyied against the AVL model. 

The structural parameters used are located in the CSV file, data/geometry/DMF_StructParam.
  - The script FrictionModel_massConv was used to study the convergence of the arc-spring masses.
  - The script FrictionModel_TorqueResp was used to simulate the transmitted torque from the DMF.
	

All content is free to be used as a help for continued research for anyone. Our research is performed for Chalmers University of Technology and Volvo Group Trucks Technology.
