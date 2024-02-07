## Overview

This repository contains a Jupyter Notebook analyzing housing prices in Boston, Massachusetts. The analysis aims to provide insights to upper management at a housing agency using statistical methods and visualizations.

## Dataset

The dataset used in this analysis is derived from the U.S. Census Service and contains information on various attributes related to housing in Boston. The dataset consists of 506 entries and 14 columns, including features such as crime rate (CRIM), zoning (ZN), proportion of non-retail business acres per town (INDUS), Charles River proximity (CHAS), nitric oxide concentrations (NOX), average number of rooms per dwelling (RM), age of the property (AGE), weighted distance to employment centers (DIS), accessibility to radial highways (RAD), property tax rate (TAX), pupil-teacher ratio (PTRATIO), percentage of lower status of the population (LSTAT), and median value of owner-occupied homes (MEDV).

## Tasks Covered in the Notebook

### Task 1: Data Familiarization

-   Imported necessary libraries.
-   Loaded the dataset into the notebook.
-   Displayed the first few rows of the DataFrame.
-   Checked information about the DataFrame including data types and non-null counts.
-   Presented summary statistics of numerical columns.
-   Checked for missing values.
-   Examined the shape and column names of the dataset.

### Task 3: Data Loading

-   Loaded the dataset using pandas from a provided URL.

### Task 4: Descriptive Statistics and Visualizations

-   Generated descriptive statistics such as boxplots, histograms, and scatter plots to visualize the distribution and relationships among various housing attributes.
-   Provided explanations for each visualization to aid understanding.

### Task 5: Statistical Analysis

1.  **Is there a significant difference in median value of houses bounded by the Charles river or not?** (T-test for independent samples)
    
    -   Conducted a T-test for independent samples to compare median values of houses bounded by the Charles River and those not bounded by it.
2.  **Is there a difference in Median values of houses for each proportion of owner-occupied units built prior to 1940 (AGE)?** (ANOVA)
    
    -   Performed an Analysis of Variance (ANOVA) to determine if there is a significant difference in median values of houses across different proportions of owner-occupied units built prior to 1940.
3.  **Can we conclude that there is no relationship between Nitric oxide concentrations and proportion of non-retail business acres per town?** (Pearson Correlation)
    
    -   Conducted a Pearson Correlation to assess the relationship between nitric oxide concentrations and proportion of non-retail business acres per town.
4.  **What is the impact of an additional weighted distance to the five Boston employment centres on the median value of owner-occupied homes?** (Regression analysis)
    
    -   Performed a Multiple Linear Regression analysis to determine the impact of an additional weighted distance to the five Boston employment centers on the median value of owner-occupied homes.

## Conclusion

The analysis provides valuable insights into various aspects of housing prices in Boston, facilitating informed decision-making for upper management. Key findings include:

-   No significant difference in median values of houses bounded by the Charles River compared to those not bounded by it.
-   Significant differences in median values of houses across different proportions of owner-occupied units built prior to 1940.
-   Lack of a significant correlation between nitric oxide concentrations and proportion of non-retail business acres per town.
-   A significant impact of an additional weighted distance to the five Boston employment centers on the median value of owner-occupied homes.

## How to Use

To replicate or further explore the analysis:

1.  Clone this repository to your local machine.
2.  Ensure you have Jupyter Notebook installed along with the required libraries mentioned in the notebook.
3.  Open the Jupyter Notebook and run each cell to execute the analysis steps.
4.  Customize the analysis or visualizations as needed for your specific requirements.
