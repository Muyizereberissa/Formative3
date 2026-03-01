# Formative3
# Bivariate Normal Distribution Analysis on Wine Quality Dataset

## Overview
This project demonstrates the implementation of the **Bivariate Normal Distribution (BVN)** from scratch in Python using the Wine Quality (Red Wine) dataset. The analysis focuses on the **alcohol** and **density** variables to compute probability density values and visualize the distribution.

## Dataset
- **Source:** Wine Quality (Red Wine) dataset
- **Columns Used:** `alcohol`, `density`
- **Format:** CSV (`winequality.csv`)
- **Note:** Ensure the CSV file is in the same folder as the notebook for the code to run correctly.

## Methodology
1. Load the dataset into a Jupyter Notebook using pandas.
2. Extract the relevant numeric columns and convert them into a NumPy array.
3. Compute the **mean vector (μ)**, **covariance matrix (Σ)**, and **correlation coefficient (ρ)** manually.
4. Implement the **Bivariate Normal Distribution (BVN) PDF** from scratch in Python (without using statistical libraries).
5. Compute the PDF values for each data point and across a grid for visualization.
6. Visualize the results using **Matplotlib**:
   - **Contour Plot:** Shows the BVN distribution with data points overlayed.
   - **3D Surface Plot:** Displays the PDF in three dimensions.

## How to Run
1. Ensure you have **Python 3.x**, **NumPy**, **pandas**, and **Matplotlib** installed.
2. Place the `winequality.csv` dataset in the same folder as the notebook.
3. Open the `Formative3.ipynb` notebook in Jupyter Notebook.
4. Run all cells in order to see the calculations and visualizations.

## Features
- Manual computation of BVN PDF without using pre-built statistical libraries.
- Clear visualizations of the bivariate distribution.
- Documented workflow with explanations of each step in Markdown cells.

## Output
- **Contour Plot:** Shows the density contours of the alcohol vs. density distribution.
- **3D Surface Plot:** Visualizes the PDF in three dimensions for better understanding.

## Notes
- The notebook is fully self-contained. Ensure the CSV file is available in the same directory for successful execution.
- This project demonstrates understanding of BVN formulas, data handling in Python, and visualization techniques.
