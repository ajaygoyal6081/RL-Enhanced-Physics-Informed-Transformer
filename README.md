# RL-Enhanced Physics-Informed Transformer

A Reinforcement Learning-based framework for solving the **1D Linear Advection Equation** using a Physics-Informed Transformer.

## Overview
- Implemented an encoder-decoder Transformer using PyTorch.
- Incorporated PDE residual, initial condition, and boundary condition losses.
- Used Q-Learning for adaptive collocation-point sampling.
- Compared Baseline, Uniform Sampling, RAR, and Q-Learning strategies.

## Technologies
Python | PyTorch | Transformers | Q-Learning | NumPy | Matplotlib

## Results

| Method | Relative L2 Error |
|---|---:|
| Baseline | 0.0584 |
| Uniform Sampling | **0.0201** |
| RAR | 0.0348 |
| Q-Learning | 0.0331 |

Uniform Sampling achieved the best overall performance, while Q-Learning improved accuracy over the baseline.

## Run the Project
Open the `.ipynb` notebook in Google Colab, enable GPU runtime, set `RUN_MODE = "FULL_RUN"`, and execute all cells.
