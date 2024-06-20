# Auto-MPG-Data-Processing-with-Pandas-and-Pipelines
# Auto-MPG Data Processing Pipeline

This repository contains the Google COLAB notebook for Assignment 2 - Pandas and Pipeline. The assignment involves loading, visualizing, and processing the auto-mpg dataset using a series of data preprocessing pipelines.

## Files

- `auto-mpg.ipynb`: The main notebook file containing all the steps and outputs as required by the assignment.
- `auto-mpg.csv`: The dataset file used in this assignment.

## Steps Performed

1. **Load Data**
   - Loaded the data from `auto-mpg.csv` into a Pandas DataFrame.
   - Checked and fixed data types.

2. **Split Data**
   - Split the data into 75% training and 25% testing sets.

3. **Visualize Data**
   - Visualized the distributions of numeric columns.
   - Categorized columns into symmetric, skewed, and categorical based on the visualizations.

4. **Build Pipeline**
   - Created pipelines for:
     - Numeric and symmetric columns (Imputation -> Standardization)
     - Numeric and skewed columns (Imputation -> Log transformation -> Standardization)
     - Categorical columns (Imputation -> One hot encoding)

5. **Train and Transform**
   - Trained the pipeline on the training data.
   - Transformed both training and testing data.
   - Printed the shapes of the processed datasets.

## Outputs

- The processed training data shape: `(XXX, YYY)`
- The processed testing data shape: `(XXX, YYY)`

## Usage

To view the notebook, navigate to the `auto-mpg.ipynb` file in the repository. The notebook includes all code, visualizations, and outputs as specified in the assignment.

## Author

Preetham

