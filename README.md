# 3x3 Grid Path Visualizer

## Overview

This repository contains a Jupyter Notebook (`3grid.ipynb`) designed to generate and visualize all possible paths on a 3x3 grid, where each path is at least four nodes long. In each path, every node of the grid is visited exactly once, showcasing unique traversals across the grid.

## Project Structure

- `3grid.ipynb`: The Jupyter Notebook containing the Python code for generating paths and visualizing them.
- `grid_paths/`: Directory containing the generated path visualizations (created after running the notebook).

## Requirements

- Python 3.x
- Jupyter Notebook
- Matplotlib

You can install the required Python packages using the following command:

```bash
pip install notebook matplotlib
```

## Usage

1. Clone this repository to your local machine.
2. Ensure you have the required dependencies installed.
3. Open the Jupyter Notebook:

   ```bash
   jupyter notebook 3grid.ipynb
   ```

4. Run the cells in the notebook to generate the visualizations.
5. The `grid_paths` directory will be created and populated with images, each representing a unique path on the 3x3 grid.

## How It Works

- The notebook creates a graph representing the 3x3 grid.
- It uses a recursive approach to find all possible paths that are at least 4 nodes long without revisiting any node.
- Each path is visualized using Matplotlib, indicating the sequence of moves across the grid.
- The generated images are saved in the `grid_paths` directory.

## Visualizations

Each image in the `grid_paths` directory illustrates a unique path across the 3x3 grid. The nodes are represented as blue dots, and the paths are indicated by red lines connecting these dots in the order they are visited.
