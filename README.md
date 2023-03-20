# NGB-Occupancy-Model
Open source Building occupancy model of Nottingham Geospatial Building (NGB) implemented using AnyLogic. There are two models implemented for electricity consumption prediction in NGB. 

NGIMainLightingPolicy-V1 is the base model implemented and validated against Estates data for NGB using the file EnergyMain2018.xlsx. Parameter variation is also implemented to run simulation over large number of times eg: 100 time with random seed. (Case study 1)
NGIMainTrajectoryPlusParameterVariation-V1 is the model built on top of the base model and modified by changing the lighting control to PIR and incorporating trajectory routes. Parameter variation is also implemented to run simulation over large number of times eg: 100 time with random seed (Case study 2)

To run simply open the project in Anylogic (AnyLogic 8 Personal Learning Edition 8.7.2 used at the moment) by pointing to the .alp model file and you will be presented with two options Simulation or Parameter variation as you hover over the run button.

To see how the simulation runs simply run any one of the option and you can fast forward the hours.

To actually record simulation data you need to check/debug the code and change it accordingly for your directory and any change in settings necessary. This project was developed for research purpose and hence some of the codes are commented or uncommented as required based on the requirment of the case study running and which settings are applied at any specific instance during the simulation.

Play around, happy modelling  !!! 
