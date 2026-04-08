City Route Optimisation using AI Search and Evolutionary Algorithms
 
Project Overview
This project addresses The Traveling Salesman problem(TSP) using two distinct AI paradigms: a Single_solution_driven Search( HIll Climbing) and a Population_Driven Evolutionary Algorithm( Genetic Algorithm). The objective is to find the shortest possible route that visits 50 cities exactly once and returns to the starting point.

The implementation is written in python ( jupyter Notebook) and adheres to PEP8 style guidlines.

Author Information

Name: Mst Sonia Khatun
Student ID: 24051725
Module: Ai For Search and Optimisation(UFCEL1-15_M)
University: University of the West of England

Key Features

Stage 1 Implementation: Stochastic Hill Climbing Algorithm for iterative route improvement.
Stage 2 Implementation: genetic Algorithm utilizing tournament selection, ordered crossover,and swap mutation.
Scalability Analysis: Systematic benchmarking across problem sizes of 10, 20,30, and 50 cities.
Performance Visualization: Real-Time Plotting of convergence history and final optimized route map.
Result Export: Automatic recording of the best city sequence to external text file.

Installation And Setup

Download git and open command prompt

Clone the Repository:  git clone [ Your-GitHub-Link-here]

Environment Requirements: Ensure you have a python environment ( Anaconda/jupyter) with the following libraries installed;
 Panda
 numpy
 Matplotlib
      
Data Placement:
Ensure The cities.csv file is located in the same directory as the jupyter Notebook.

Usage   
Launch jupyter Notebook or JupyterLab.
Open  AI_For_Search_and_Optimisation.ipynb
Run all cells to execute the scalability test and generate performance metrics.
View the best_route_sequence.txt file generated in the project folder for the final 50 city output.


Methodology Summary

Hill Climbing: Operates with a single candidate solution, adjusting it iteratively to improve fitness based on total distance.
Genetic Algorithm: uses a population of chromosomes(route) to evolve better solutions Over  generations, balancing exploration and exploitation.
Heuristics; Euclidean distance is utilized as the primary metric for cose calculation between coordinates.
 Repository Structure
AI_For_Search_and_Optimisation.ipynb: Main implementation notebook following PEP8 standards.
Cities.csv: Dataset containing city coordinates.
best_route_sequence.txt: External record of the optimal route found.
Performance_comparison.png: generated convergence graph
README.md: project documentation.

References
Alanzi, E., & Menai, M. E. B. (2025). Solving the traveling salesman problem with machine learning.
Mamatova, Z., & Abdumajidova, M. (2025). Mathematical modeling and optimal solutions.
Russell, S. and Norvig, P. Artificial Intelligence: A Modern Approach.

