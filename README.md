# City Route Optimisation using AI Search and Evolutionary Algorithms

## 📌 Project Overview
This project addresses the **Traveling Salesman Problem (TSP)** by designing, implementing, and benchmarking two distinct artificial intelligence search paradigms:
* **Single-solution-driven Search:** Steepest-Ascent/Stochastic Hill Climbing using a local 2-opt neighborhood structure.
* **Population-driven Evolutionary Algorithm:** A Genetic Algorithm (GA) featuring tournament selection, order-based crossover (OX), and mutation operators.

The primary objective is to find the shortest possible Euclidean route that visits a set of **50 cities exactly once** and returns to the starting location. The underlying engine is built entirely in Python (Jupyter Notebook) and adheres to clean, readable **PEP8 coding standards**.

---

## 👤 Author Information
* **Name:** Mst Sonia Khatun
* **Student ID:** 24051725
* **Module:** AI For Search and Optimisation (UFCEL1-15_M)
* **Institution:** University of the West of England (UWE Bristol)

---

## 🚀 Key Features
* **Iterative Local Search:** A complete implementation of Hill Climbing utilizing full 2-opt neighborhood exploration.
* **Evolutionary Core:** A population-based Genetic Algorithm tracking elitism, tournament selection, multiple crossover types (OX/PMX), and advanced mutation techniques (Inversion/Swap).
* **Scalability Benchmarking:** Performance testing across growing problem instances of 10, 20, 30, 40, and 50 cities to map execution behaviors.
* **Statistical Validation:** Integrated Wilcoxon signed-rank tests to mathematically verify algorithmic performance gaps across multiple runs.
* **Performance Visualization:** Auto-generated dynamic convergence plots tracking optimization trends and plotting final route layouts.
* **Automated Exporting:** The best city sequence is automatically captured and structured to an external `.txt` file for secondary pipeline use.

---

## 🛠️ Installation & Setup

### 1. Environment Requirements
Ensure you have a Python environment setup (such as an Anaconda distribution or virtual environment) with the following foundational data science libraries installed:
```bash
pip install pandas numpy matplotlib scipy

---
## 📁 Data Placement
Ensure the `Cities.csv` file is located in the same directory as the Jupyter Notebook.

---

## 💻 Usage
1. Launch **Jupyter Notebook** or **JupyterLab**.  
2. Open `AI_For_Search_and_Optimisation.ipynb`.  
3. Run all cells to execute the scalability test and generate performance metrics.  
4. View the `best_route_sequence.txt` file generated in the project folder for the final 50-city output.

---

## 🧠 Methodology Summary
* **Hill Climbing:** Operates with a single candidate solution, adjusting it iteratively to improve fitness based on total distance.  
* **Genetic Algorithm:** Uses a population of chromosomes (routes) to evolve better solutions over generations, balancing exploration and exploitation.  
* **Heuristics:** Euclidean distance is utilized as the primary metric for cost calculation between coordinates.

---

## 📂 Repository Structure
* `AI_For_Search_and_Optimisation.ipynb` – Main implementation notebook following PEP8 standards  
* `Cities.csv` – Dataset containing city coordinates  
* `best_route_sequence.txt` – External record of the optimal route found  
* `Performance_comparison.png` – Generated convergence graph  
* `README.md` – Project documentation  

---

## 📚 References
* Alanzi, E., & Menai, M. E. B. (2025). Solving the traveling salesman problem with machine learning.  
* Mamatova, Z., & Abdumajidova, M. (2025). Mathematical modeling and optimal solutions.  
* Russell, S., & Norvig, P. *Artificial Intelligence: A Modern Approach.*
