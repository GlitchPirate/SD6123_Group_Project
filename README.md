# Privacy_Project_add_ablation

![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [How to Run](#how-to-run)
- [Project Structure](#project-structure)
- [Notes](#notes)
- [Results Preview](#results-preview)

## Introduction
This project focuses on **instance-optimal sum estimation** under **Local Differential Privacy (LDP)**.  
It implements and compares multiple privacy-preserving mechanisms:
- Randomized Response (RR)
- Binary Tree Encoding (BTE)
- Laplace Mechanism (Laplace Noise)

An **ablation study** is included to further analyze the influence of specific components and design choices.

The code is structured in a modular format within a Jupyter Notebook.

## Features
- Data cleaning and preprocessing
- Randomized Response implementation
- Binary Tree Encoding under LDP
- Laplace Mechanism for baseline comparison
- Ablation experiments
- Visualization of error trends, privacy loss, and runtime
- Easy extension for new datasets

## Installation

Install the required dependencies:
```bash
pip install numpy pandas matplotlib scikit-learn seaborn scipy
```

Recommended environment:
- Python 3.8+
- Jupyter Notebook or Jupyter Lab

## How to Run

1. **Open the Notebook**  
   Launch `Privacy_Project_add_ablation.ipynb` in Jupyter Notebook or Jupyter Lab.

2. **Run Step-by-Step**  
   The notebook is divided into modular sections:
   - Step 1: Data Cleaning & Preprocessing
   - Step 2: Randomized Response Encoding
   - Step 3: Binary Tree Encoding
   - Step 4: Laplace Mechanism Comparison
   - Step 5: Ablation Study
   - Step 6: Visualization and Summary

3. **Changing the Dataset**  
   To use a new dataset, simply update the data path at the beginning of the notebook.  
   No major code modification is needed.

4. **Saving Outputs**  
   Results and plots can be saved locally from within the notebook.

## Project Structure
```
Privacy_Project_add_ablation.ipynb
├── Data Preprocessing
├── Randomized Response
├── Binary Tree Encoding
├── Laplace Mechanism Comparison
├── Ablation Studies
└── Visualization and Results
```

## Notes
- Some modules may take time to execute depending on data size.
- The default experiments use synthetic datasets or pre-cleaned real data.
- Visualization outputs include error curves, runtime comparisons, and accuracy metrics under different privacy budgets.

## Results Preview
The final notebook includes:
- Comparative analysis between different privacy mechanisms
- Effects of specific design choices through ablation
- Graphical summaries and detailed discussion

Example plots:
- Error vs. Privacy Budget
- Runtime comparisons
- Impact of ablation settings on accuracy

