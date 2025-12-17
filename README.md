# City-Route-Optimisation-GA
AI project demonstrating Genetic Algorithm and A* search for cities route optimisation

Conceptual Design and Genetic Algorithm  Approach to City Route optimisation 
Author Name 
Mst Sonia Khatun 
ID 
Student Id:24051725 

#Abstract 
This Assignment demonstrates the application of Ai search and Optimization techniques on a 
provided cities dataset. A simple Genetic Algorithm was used to explore possible routes 
between cities, with the objective of minimising total travel distance. The study focuses on 
algorithm design, basic implementation, and conceptual understanding of optimisation 
principles,including the balance between exploration and exploitation. 
1.Introduction 
AI search and optimisation algorithms are important tools for solving problems like route 
planning, scheduling and resource allocation. The aim of this assignment is to demonstrate a 
basic understanding of these algorithms using a cities dataset, focusing on a simple genetic 
Algorithm approach. Due to time constraints and other circumstances, full implementation is  
simple and conceptual. 

2. Problem Definition 
   1.State Space: Each city in the dataset is a state. 
   2.Goal: find a route visiting all cities with minimal total distance. 
   3.Constraints: Each city must be visited once, the route start at one city and ends at 
    another(Like loops). 
   4. Dataset: Cities provided with X, Y coordinates. 
3. Literature Review / Related Work 
   1.Classical search algorithms such as A or Dijkstra are often used for shortest problems. 
   2. Genetics algorithms are population based optimization methods suitable for route planning 
   and combinatorial problems like the Travelling Salesman Problem. 
   3. GA benefits: robustness, exploration of multiple solutions. 
   4. GA limitation:  results vary based on parameter tuning, may not guarantee the optimal 
   solution. 
4.Methodology 
  1. Chromosome: Ordered list of cities(route) 
  2. Fitness Function: Inverse of total distance(shorter = better) 
  3. Selection: Top solutions are preferred 
  4. Mutation: Swap two cities to maintain diversity. 
  5. Generations: repeat mutation And selection to evolve better solutions. 
 
It is a simple GA demonstrates MO2 concepts: optimisation, parameter tuning and exploration 
vs exploitation 
 
 
4.1 Single - State Search Algorithm ( A*) 
    A* search is a classical single- state search algorithm used to find an optimal path 
between a start state and a goal state. It evaluates nodes by combining the actual cost 
of the start note, g(n). And a heuristic estimate to the goal, h(n). In this assessment, A* 
is included to demonstrate a traditional AI search approach and to provide a conceptual 
comparison with evolutionary algorithms. The  heuristic function used is the Euclidean 
distance between cities, which is suitable for spatial optimization problems. 
 
Pseudocode: 
 Initialize open list with start node 
 While open list is not empty 
           Select node with lowest f(n) = g(n) + h(n) 
           If node is goal: return solution 
           Expand nodes and update costs. 
 
4.2 Evolutionary Algorithm(Genetic Algorithm) 
        A Genetic Algorithm (GA) was applied to solve the city optimization problem, which is 
similar to the Travelling salesman problem. Each chromosome  represents a possible route 
visiting all cities exactly once. The fitness function is defined as the total euclidean distance of 
the route, where shorter distance corresponded to better fitness. The algorithm evolves 
solutions over multiple generations using selection, crossover, and  mutation operators. This 
approach allows effective exploration of a large search space and balance exploration and 
exploitation through parameter tuning. 


5. Implementation Details 
 
    ###Code 

6.Result and Analysis 
  1. Expected behaviour: Shorter routes improve over generations. 
  2. Best route found : printed by by code 
  3. Observation: Small population size and few generations make it quick but approximate.        
  Mutation prevents early convergence. 

7. Comparison and Discussion 
   1. GA vs single state search 
       a. GA: stochastic, explores many solutions, scalable to larger problems 
       b. Single state search A and Dijkstra : deterministic, optimal, but less flexible for  
       large datasets 
   2. Limitation: GA may not find an absolute short path, performance depends on population  
   size and mutation rate.  

8. Conclusion And future work 
   1. Conceptual GA successfully demonstrate optimisation principles 
   2. Future work could include: 
       a. Implementing a full A* search on the cities dataset. 
       b. Increasing population size and generations for better solutions 
       c. Comparing GA with other evolutionary techniques 

9. References 
     1. Russell, S. And Norvig, P . Artificial intelligence: A Modern Approach 
     2. Goldberger, D.E., Genetic Algorithms in Search, Optimization, and machine learning 
     3. Module lecture notes
