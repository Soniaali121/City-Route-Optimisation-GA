#City Route Optimisation using AI Search and Evolutionary Algorithms
 

##Project Overview
This project addresses The **Traveling Salesman problem(TSP)** using two distinct AI paradigms: a 1.**Single_solution_driven Search**:Stochastic HIll Climbing
2. **Population_Driven Evolutionary Algorithm**:Genetic Algorithm. 

The objective is to find the shortest possible route that visits 50 cities exactly once and returns to the starting point.
The implementation is written in python ( jupyter Notebook) and adheres to PEP8 style guidlines.
---

##Author Information

-**Name**: Mst Sonia Khatun
-**Student ID**: 24051725
-**Module**: Ai For Search and Optimisation(UFCEL1-15_M)
-**University**: University of the West of England




##Key Features

-**Stage 1 Implementation**: Stochastic Hill Climbing Algorithm for iterative route improvement.

-**Stage 2 Implementation**: genetic Algorithm utilizing tournament selection, ordered crossover,and swap mutation.

-**Scalability Analysis**: Systematic benchmarking across problem sizes of 10, 20,30, and 50 cities.

-**Performance Visualization**: Real-Time Plotting of convergence history and final optimized route map.

-**Result Export**: Automatic recording of the best city sequence to external text file.
----

##Installation And Setup
1. **Clone the Repository**:
   ```bash
   git clone [ Your-GitHub-Link-here]


#Environment Requirements: Ensure you have a python environment ( Anaconda/jupyter) with the following libraries installed;
 Panda
 numpy
 Matplotlib
      
##Data Placement:
Ensure The cities.csv file is located in the same directory as the jupyter Notebook.



##Usage   
1. Launch jupyter Notebook or JupyterLab.
2. Open  AI_For_Search_and_Optimisation.ipynb
3. Run all cells to execute the scalability test and generate performance metrics.
4. View the best_route_sequence.txt file generated in the project folder for the final 50 city output.


##Methodology Summary

1. **Hill Climbing**: Operates with a single candidate solution, adjusting it iteratively to improve fitness based on total distance.
2.**Genetic Algorithm**: uses a population of chromosomes(route) to evolve better solutions Over  generations, balancing exploration and exploitation.
3.**Heuristics**: Euclidean distance is utilized as the primary metric for cose calculation between coordinates.
 Repository Structure
4.**AI_For_Search_and_Optimisation.ipynb**: Main implementation notebook following PEP8 standards.
5.**Cities.csv**: Dataset containing city coordinates.
6.**best_route_sequence.txt**: External record of the optimal route found.
7.**Performance_comparison.png**: generated convergence graph
8.**README.md**: project documentation.



References
Alanzi, E., & Menai, M. E. B. (2025). Solving the traveling salesman problem with machine learning.
Mamatova, Z., & Abdumajidova, M. (2025). Mathematical modeling and optimal solutions.
Russell, S. and Norvig, P. Artificial Intelligence: A Modern Approach.
