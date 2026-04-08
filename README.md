# City Route Optimisation using AI Search and Evolutionary Algorithms

## Project Overview
This project addresses the **Traveling Salesman Problem (TSP)** using two distinct AI paradigms:  

1. **Single-solution-driven Search**: Stochastic Hill Climbing  
2. **Population-driven Evolutionary Algorithm**: Genetic Algorithm  

The objective is to find the shortest possible route that visits **50 cities exactly once** and returns to the starting point.

The implementation is written in **Python (Jupyter Notebook)** and adheres to **PEP8 style guidelines**.

---

## Author Information
- **Name:** Mst Sonia Khatun  
- **Student ID:** 24051725  
- **Module:** AI For Search and Optimisation (UFCEL1-15_M)  
- **University:** University of the West of England  

---

## Key Features
- **Stage 1 Implementation:** Stochastic Hill Climbing for iterative route improvement.  
- **Stage 2 Implementation:** Genetic Algorithm using tournament selection, ordered crossover, and swap mutation.  
- **Scalability Analysis:** Benchmarking across problem sizes of 10, 20, 30, and 50 cities.  
- **Performance Visualization:** Real-time plotting of convergence history and final optimized route map.  
- **Result Export:** Automatic recording of the best city sequence to an external text file.

---

## Installation and Setup
1. **Clone the Repository**:  
   ```bash
   git clone [Your-GitHub-Link-Here]


## Environment Requirements
Ensure you have a Python environment (Anaconda/Jupyter) with the following libraries installed:  
- pandas  
- numpy  
- matplotlib  

---

## Data Placement
Ensure the `Cities.csv` file is located in the same directory as the Jupyter Notebook.

---

## Usage
1. Launch **Jupyter Notebook** or **JupyterLab**.  
2. Open `AI_For_Search_and_Optimisation.ipynb`.  
3. Run all cells to execute the scalability test and generate performance metrics.  
4. View the `best_route_sequence.txt` file generated in the project folder for the final 50-city output.

---

## Methodology Summary
1. **Hill Climbing:** Operates with a single candidate solution, adjusting it iteratively to improve fitness based on total distance.  
2. **Genetic Algorithm:** Uses a population of chromosomes (routes) to evolve better solutions over generations, balancing exploration and exploitation.  
3. **Heuristics:** Euclidean distance is utilized as the primary metric for cost calculation between coordinates.

---

## Repository Structure
- `AI_For_Search_and_Optimisation.ipynb` – Main implementation notebook following PEP8 standards  
- `Cities.csv` – Dataset containing city coordinates  
- `best_route_sequence.txt` – External record of the optimal route found  
- `Performance_comparison.png` – Generated convergence graph  
- `README.md` – Project documentation  

---

## References
- Alanzi, E., & Menai, M. E. B. (2025). *Solving the traveling salesman problem with machine learning.*  
- Mamatova, Z., & Abdumajidova, M. (2025). *Mathematical modeling and optimal solutions.*  
- Russell, S., & Norvig, P. *Artificial Intelligence: A Modern Approach.*
