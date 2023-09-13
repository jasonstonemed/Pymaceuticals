# Pymaceuticals

# Tumor Volume Analysis README

## Overview
This project focuses on the analysis of tumor volume data from a scientific study involving various drug regimens and their impact on mice. The code provided performs data cleaning, statistical analysis, and data visualization to gain insights from the dataset.

## Code Structure
The code is structured into distinct sections, each addressing specific tasks and aspects of the data analysis.

### Dependencies and Setup
The initial section of the code sets up the necessary dependencies, ensuring you have the required libraries installed: `matplotlib`, `pandas`, and `scipy.stats`. It also defines file paths for mouse metadata and study results, reads the data, and merges it into a single dataset.

### Data Cleaning
This section handles duplicate data by identifying and displaying duplicate entries. It then creates a clean DataFrame by removing these duplicates, ensuring data accuracy.

### Summary Statistics
The code generates summary statistics for each drug regimen, including mean, median, variance, standard deviation, and standard error of the mean (SEM) of the tumor volume. It organizes this information into a summary table, making it easy to compare the effects of different drug regimens.

### Data Visualization
The project includes several data visualization techniques to provide a comprehensive understanding of the dataset:

#### 1. Bar Plot
This visualization presents a bar plot showing the total number of timepoints for each drug regimen. It uses both Pandas and Matplotlib to create the plot, providing a clear overview of the data distribution.

#### 2. Pie Plot
A pie plot illustrates the distribution of female versus male mice. It calculates the percentages and displays them in an easily digestible format.

#### 3. Box Plot
A box plot depicts the distribution of tumor volume for each treatment group. It visually represents the spread and central tendency of the data, allowing for comparisons between different drug regimens.

#### 4. Line Plot
A line plot shows how tumor volume changes over time for a specific mouse treated with Capomulin. This plot helps visualize the impact of treatment on an individual subject.

#### 5. Scatter Plot with Regression Line
A scatter plot visualizes the relationship between mouse weight and average tumor volume for mice treated with Capomulin. It also includes a linear regression line and correlation coefficient to analyze the association between these variables.

Readme assistance via ChatGPT
