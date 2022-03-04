# The implementation of Genetic Algorithm and Particle Swarm Optimisation on Uncapacitated Single Allocation p-Hub Location Problem (U-SApHLP)

### Executive Summary
This project was completed in February 2022 as a final project for Soft Computing course at the University of Edinburgh. In this study, Genetic Algorithm (GA) and Particle Swarm Optimisation (PSO) were implemented to address uncapacitated Single Allocation p-Hub Location Problems (SApHLP). GA and PSO were run in Python on Macbook Apple M1 with 8 GB of RAM. Both algorithms were evaluated based on the average Total Network Cost (TNC), computational time, and optimality gap. The result suggested that both algorithms were effective to obtain nearly optimal solutions with less computational time, with PSO performing better than GA.

### Problem Description
This study deals with U-SApHLP where each demand point must only be connected to a single hub facility and any inbound and outbound flow of each demand point must be carried out via the hub. Locations are set in discrete values with unlimited capacity. The optimisation model was run on three problem instances, CAB dataset (n=25), TR dataset (n=55 & 81) and RGP (n=100 & 130). Each scenario has various number of nodes, hubs, and discount rate, with a total of 20 test problems evaluated. Every test problem is run 10 times to evaluate the model performance stability against different initial solutions.

### Computational results
The computational experiment presented evidences on the effectiveness of metaheuristics algorithms to address U-SApHLP. Two algorithms—GA and PSO—were run in Python on 20 problem instances with varying number of nodes, hubs, and discount rate. Although both algorithms are proven effective to obtain nearly optimal solutions, PSO generally performs better than GA, particularly in terms of computational times and optimality gap. However, both algorithms were unable to find the optimal solutions for larger instances (n >= 100), especially for problems with alpha = 0.8. This indicates that the current model still requires some adjustments to cater larger instances as well. One of the suggestions is to increase the number of population for GA, but the drawbacks would be the inclining computational times. Overall, the models presented in this study will beneficial for businesses if minimising computational burden is the top priority. However, if the objective is to produce optimal solution, the models still needs some improvements.

##### Author: © Hutami Nadya Larasati 2022

