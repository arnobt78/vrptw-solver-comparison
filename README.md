# vrptw-solver-comparison
Solving Vehicle Rounting Problem with Time Windows using multiple Classic Heuristic, Metaheuristic algorithms (Hybrid Genetic Search (HGS), Guided Local Search (GLS), Ant Colony Optimisation (ACO), Simulated Annealing (SA)), then comparing the results with each one's results and represent it in the graph. This was my master's thesis project.

# keywords
Vehicle Routing Problems with Time Window (VRPTW), Hybrid Genetic Search (HGS), Guided Local Search (GLS), Ant Colony Optimization (ACO), Simulated Annealing (SA), MACS-VRPTW, Genetic Algorithm (GA), Exact, Heuristics, Metaheuristics, Machine Learning Algorithms, GRASP, Local Search (LS), Neighborhood Search, OR-Tools, VRP, VRPTW, Vehicle Routing Problems (VRP), pyVRP.

# Note
Using the Python Jupyter Notebook is highly advised. While compiling, each model executes independently. However, if you run the code straight from main.py , the application may crash and display errors due to the ACO procedure’s use of multiple threads! However, it functions perfectly now that I’m using the Python Jupyter Notebook code.

# Development

## Create venv

```sh
python -m venv .venv
```

## Activate venv

```sh
. .venv/bin/activate
```

## Install requirements

```sh
pip install -r requirements.txt
