# Matplotlib for Data Science

A structured, practice-driven curriculum for data visualization in Python. It is the foundation for **exploratory data analysis (EDA)** and **model evaluation** in machine learning workflows.

![Python](https://img.shields.io/badge/Python-3.9%2B-blue)
![Matplotlib](https://img.shields.io/badge/Matplotlib-visualization-orange)
![Jupyter](https://img.shields.io/badge/Jupyter-notebooks-F37626)

## Overview

Before training any model, you need to understand your data: its distribution, outliers, relationships and trends. This repository builds that skill step by step. Each of the 11 modules pairs a concept notebook with a practice notebook of applied tasks and conceptual questions.

## Why this matters for ML

| Visualization skill | Where it's used in AI/ML |
|---|---|
| Histograms, box plots | Checking feature distributions and detecting outliers before modeling |
| Scatter plots | Inspecting feature relationships and correlations |
| Line plots | Plotting training/validation loss and metric curves |
| Subplots | Comparing multiple features or model results side by side |
| Time series plots | Trend and seasonality analysis |
| Pandas/NumPy plotting | Working directly with real datasets |

## Curriculum

| Module | Topic | Key concepts |
|---|---|---|
| 01 | Matplotlib Basics | Figures, axes, titles, labels |
| 02 | Line Plots | Styles, markers, multi-series comparison |
| 03 | Scatter Plots | Color, size, transparency, relationships |
| 04 | Bar Charts | Vertical/horizontal, categorical comparison |
| 05 | Histograms | Bins, distributions, histogram vs bar chart |
| 06 | Box Plots | Quartiles, IQR, outliers, grouped comparison |
| 07 | Pie Charts | `autopct`, `explode`, `startangle` |
| 08 | Subplots | Multi-panel layouts, figsize, annotations, styling |
| 09 | Datetime Series | Time-indexed data, date formatting |
| 10 | Visualization with NumPy | `arange`, `linspace`, multi-dataset plots, legends |
| 11 | Visualization with Pandas | DataFrame-based plotting |

## Repository structure

```
matplotlib-for-datascience/
├── 01_matplotlib_basics/
├── 02_line_plots/
├── ...
├── 11_visualization_with_pandas/
│   ├── 01_introduction.ipynb    # concepts + examples
│   └── 02_practise.ipynb        # tasks + conceptual questions
├── requirements.txt
└── README.md
```

## Setup

```bash
git clone https://github.com/ibrahimkhanmohammad/matplotlib-for-datascience.git
cd matplotlib-for-datascience
python -m venv venv
source venv/bin/activate        # Windows: venv\Scripts\activate
pip install -r requirements.txt
jupyter notebook
```

**Dependencies:** NumPy, Pandas, Matplotlib, Jupyter, ipykernel

## Author

**Ibrahim**, Computer Science student specializing in Data Science and AI/ML.

[GitHub](https://github.com/ibrahimkhanmohammad) · [LinkedIn](https://www.linkedin.com/in/ibrahimkhanmohammad/)
