
# Artificial Intelligence Pathfinding Algorithms Project

## Project Overview
This project explores the implementation and analysis of several advanced pathfinding algorithms within artificially generated gridworld environments. Aimed at navigating through complex mazes, this study compares the performance of A*, Repeated Forward A*, Repeated Backward A*, and Adaptive A* algorithms to understand their efficiencies and the impact of heuristic functions and tie-breaking strategies.

### Contributors
- Diego Quito
- Haider Ali
- Steven Packard

### Institution
Rutgers University, Spring 2024

## Setup and Installation
Ensure you have Python 3.x installed along with the following libraries:
- NumPy
- Matplotlib

To install the required packages, run:
```bash
pip install numpy matplotlib
```

<!-- ## Running the Project
1. **Generate Gridworld Environments**: First, generate the 50 unique gridworld environments by running the environment generation script:
   ```bash
   python generate_maze.py
   ```
2. **Execute Pathfinding Algorithms**: To compare the pathfinding algorithms, execute:
   ```bash
   python run_pathfinding.py
   ```
   This script will automatically perform the analysis and generate visualizations for the pathfinding outcomes. -->

## Key Features
- **Algorithm Implementation**: Includes comprehensive implementations of A*, Repeated Forward A*, Repeated Backward A*, and Adaptive A*.
- **Environment Generation**: Uses a depth-first search algorithm with random tie-breaking to create challenging maze-like gridworlds.
- **Performance Analysis**: Compares algorithms based on path length, runtime, and cells expanded.
- **Statistical Significance Testing**: Assesses the performance differences between algorithms using a t-test for independent samples.

## Results
Our analysis revealed Adaptive A* as the superior algorithm in terms of runtime efficiency, underscoring the importance of dynamic heuristic updates in complex environments. Detailed results and visualizations can be found in the `results` folder.

## Conclusion
This project highlights the practical applications and theoretical implications of pathfinding algorithms in artificial intelligence, offering valuable insights into heuristic optimization and algorithmic efficiency in gridworld navigation.

## References
- Python Software Foundation. (n.d.). [Python Language Reference](https://www.python.org)
- Hunter, J. D., Droettboom, M., & the Matplotlib Development Team. (n.d.). [Matplotlib: Visualization with Python](https://matplotlib.org)
- Cohen, P. R. (1995). Empirical Methods for Artificial Intelligence. MIT Press.

