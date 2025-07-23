# Task 1: Exploring and Visualizing the Iris Dataset

## Objective
To understand how to read, summarize, and visualize a simple dataset using pandas, matplotlib, and seaborn.

## Dataset
The Iris dataset contains measurements of 150 iris flowers from three different species: setosa, versicolor, and virginica. Each sample includes:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

## Approach

1. **Data Loading**
   - Used seaborn’s built-in Iris dataset.
   - Loaded into a pandas DataFrame.

2. **Data Inspection**
   - Used `.shape`, `.columns`, and `.head()` to understand the structure.

3. **Visualizations**
   - **Scatter Plot**: Showed relationship between petal length and petal width.
   - **Histogram**: Visualized the distribution of sepal lengths.
   - **Box Plot**: Checked for outliers and spread of petal lengths by species.

## Conclusion
The visualizations clearly showed the separation between species based on petal measurements. Setosa flowers tend to have shorter petals, while virginica has longer ones. This makes the Iris dataset useful for practicing classification problems in machine learning.
