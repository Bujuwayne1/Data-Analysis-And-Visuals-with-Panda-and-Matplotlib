# Python Data Analysis Assignment

## Overview
This project demonstrates a complete data analysis workflow using Python, covering data loading, cleaning, exploratory analysis, and visualization with the **Iris dataset**. The tasks are implemented using `pandas` for data manipulation and `matplotlib` for visualizations.

## Tasks Completed
1. **Data Loading & Exploration**:  
   - Loaded the Iris dataset from `sklearn.datasets`.  
   - Inspected structure, data types, and missing values.  

2. **Basic Data Analysis**:  
   - Computed statistics (mean, median, etc.) using `.describe()`.  
   - Grouped data by species and analyzed mean petal length.  

3. **Data Visualization**:  
   - Created 4 plot types:  
     - Line chart (simulated trend).  
     - Bar chart (mean sepal width by species).  
     - Histogram (petal length distribution).  
     - Scatter plot (sepal vs. petal length by species).  

## Key Findings
- **Species Differentiation**:  
  - Virginica (species 2) has the longest petals (5.55 cm avg), while Setosa (species 0) has the shortest (1.46 cm avg).  
- **Sepal Width**: Setosa has the widest sepals.  
- **Bimodal Distribution**: Petal lengths cluster into two distinct groups (short vs. long).  

## Code Structure
```plaintext
iris_analysis/
│── iris_analysis.py    # Main script with all tasks
│── README.md           # This file
└── plots/              # Generated visualizations (optional)
