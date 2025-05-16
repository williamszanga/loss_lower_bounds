# Irreducible Loss Floors in Gradient-Based Optimization and Energy Footprint

This repository provides the official code and reproducible experiments accompanying the paper **"Irreducible Loss Floors in Gradient-Based Optimization and Energy Footprint"**. It implements the numerical estimation of lower bounds on the training loss under idealized convergence assumptions, and illustrates the framework's behavior across various learning problems.

## Contents

The main experiments and plots discussed in the paper are implemented in the following notebooks:

- **`graphs_found_in_the_paper.ipynb`**  
  Generates most of the illustrative figures and toy examples discussed throughout the paper, including convergence dynamics and irreducible floor visualizations.

- **`application_to_linear_model.ipynb`**  
  Demonstrates the irreducible loss floor in the setting of a simple linear regression model. Useful for building intuition in a tractable case.

- **`application_to_MNIST.ipynb`**  
  Applies the framework to a shallow convolutional neural network trained on the MNIST dataset. Shows how lower bounds behave in a real-world but lightweight setup.

- **`application_to_Cifar100.ipynb`**  
  Applies the framework to a moderately deep CNN trained on CIFAR-100 using a GPU backend. Highlights computational constraints and shows how optimizer-specific refinements impact bounds.

## Getting Started

You can run these notebooks using [Google Colab](https://colab.research.google.com/) or in a local Python environment. We recommend using:

- Python ≥ 3.8  
- PyTorch ≥ 2.0  
- Jupyter Notebook or Jupyter Lab  


## Citing

````
@misc{wkzng2025iredfloor,
  title={Irreducible Loss Floors in Gradient-Based Optimization and Energy Footprint},
  author  = {Anonymous Author},
  year    = {2025},
  eprint  = {arXiv:2506.xxxxx},
  archivePrefix = {arXiv},
  primaryClass  = {cs.LG},
  note    = {Under review at NeurIPS 2025}
}
````