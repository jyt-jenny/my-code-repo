# My Algorithm Project

## Overview
This project implements a novel node influence ranking algorithm for complex networks, integrating iterative K-shell decomposition, node degree, and neighbor information.

## Dependencies
- Python 3.8+
- NetworkX
- NumPy
- Matplotlib
- itertools

## Code Structure
Monotonicity.py: Used to calculate the monotonicity and ranking results of all algorithms.
Monotonicity-line.py: Used to plot the results based on the monotonicity.
kendall.py: Used to calculate the Kendall coefficient (consistency) between the ranking results of all algorithms and the SIR propagation ranking results.
kendall-line.py: Used to plot the Kendall coefficient graph for all algorithms across all networks.
SIR.py: Implements the SIR model propagation.
top10.py: Plots the SIR propagation curves for the top 10 nodes in the ranking results of all algorithms.
time.py: Used to calculate the execution time of the ranking results for all algorithms.
time_line.py: Used to plot a bar chart based on the execution time.
CCDF-line.py: Used to plot the CCDF (Complementary Cumulative Distribution Function) curve.
dengjipinci.py :Plot the frequency distribution of the number of nodes in each rank based on the ranking results of all algorithms.


## Special Note 
Due to the differences in dataset formats and SIR propagation parameters, the dataset acquisition, SIR propagation parameters, and filenames for storing results need to be manually modified in all code files.
