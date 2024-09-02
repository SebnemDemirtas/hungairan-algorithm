# Hungarian Algorithm Implementation

This repository contains a Python implementation of the Hungarian Algorithm, which is used to solve assignment problems. This implementation was developed by Sebnem Demirtas for INDR363, Homework 2, on November 2nd, 2022.

## Table of Contents
- [Introduction](#introduction)
- [Requirements](#requirements)
- [Usage](#usage)

## Introduction

The Hungarian Algorithm, also known as the Munkres or Kuhn-Munkres algorithm, is an optimization algorithm that solves the assignment problem. The problem involves assigning tasks to agents in a way that minimizes the total cost or maximizes the total efficiency.

This implementation takes a cost matrix as input and returns the optimal assignment along with the objective function value, which represents the minimal cost.

## Requirements

To run the code in this repository, you need:

- Python 3.x
- NumPy

You can install NumPy using pip if you don't have it already:

```bash
pip install numpy
```

## Usage

1. Clone the repository:
   
```python3
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name
```

2. Run the Jupyter Notebook or script containing the Hungarian algorithm. You can execute the algorithm with a custom cost matrix as shown below:
```python3
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name
```
3. The output will show:
    
    The original cost matrix
    The modified matrix after performing the algorithm
    The optimal assignments
    The objective function value
