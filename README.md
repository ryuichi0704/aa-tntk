# Neural Tangent Kernels for Axis-Aligned Tree Ensembles

This repository provides Jupyter notebooks that support the visualizations in the paper:

- Kanoh, R., Sugiyama, M.: **Neural Tangent Kernels for Axis-Aligned Tree Ensembles**, ICML 2024

## Contents

### 1. Visualization of the Kernel
- `kernel_asymptotic.ipynb`
  - Demonstrates the convergence of the kernel induced by a finite tree to a closed-form kernel as the number of trees increases.
- `kernel_rotate.ipynb`
  - Examines variations in kernel behavior with different feature selections.

### 2. Visualization of the Training Trajectory
- `track.ipynb`
  - Illustrates model behavior during training under different conditions (AAA and AAI) using kernels.
- `track_oblivious_conversion.ipynb`
  - Depicts how NTKs induced by trees with arbitrary structures can be represented using NTKs induced by oblivious trees.

### 3. Visualization of Multiple Kernel Learning (MKL) Results
- `mkl_tictactoe.ipynb`
  - Analyzes the application of MKL to the tic-tac-toe dataset.
- `mkl_multiple_data.ipynb`
  - Explores MKL application across various UCI datasets.

## Setup and Usage

### Installation
To set up the necessary environment:

```sh
pip install -r requirements.txt
```

### Running the Notebooks
To open and run the notebooks:

```sh
jupyter notebook
```
