# Pymaceuticals Inc. Clinical Study Analysis - Data Visualization

## Overview

This project analyzes data from a clinical study conducted by Pymaceuticals Inc., a pharmaceutical company specializing in anti-cancer medications. The study focused on squamous cell carcinoma (SCC), a commonly occurring form of skin cancer. The goal was to compare the performance of Pymaceuticals’ drug of interest, Capomulin, against other treatment regimens.

## Files

The following files are used in this project:
- `Mouse_metadata.csv`: Contains metadata about the mice used in the study.
- `Study_results.csv`: Contains the results of the study, including tumor volumes and time points.
- `pymaceuticals_starter.ipynb`: The Jupyter Notebook containing the analysis and visualizations.
- `README.md`: This file.

## Instructions

The analysis is broken down into the following tasks:

### 1. Prepare the Data
- Merge the `mouse_metadata` and `study_results` DataFrames into a single DataFrame.
- Display the number of unique mice IDs.
- Identify and remove any duplicate time points for each mouse.

### 2. Generate Summary Statistics
- Calculate the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.

### 3. Create Bar Charts and Pie Charts
- Generate bar charts to show each drug regimen's total number of time points.
- Generate pie charts to show the study's distribution of female versus male mice.

### 4. Calculate Quartiles, Find Outliers, and Create a Box Plot
- Calculate the final tumor volume of each mouse across four promising treatment regimens (Capomulin, Ramicane, Infubinol, and Ceftamin).
- Determine quartiles, IQR, and potential outliers.
- Generate a box plot to show the distribution of the final tumor volume for each treatment group.

### 5. Create a Line Plot and a Scatter Plot
- Generate a line plot of tumor volume versus time point for a single mouse treated with Capomulin.
- Generate a scatter plot of mouse weight versus the average observed tumor volume for the Capomulin treatment regimen.

### 6. Calculate Correlation and Regression
- Calculate the correlation coefficient between mouse weight and average tumor volume for the Capomulin regimen.
- Plot the linear regression model on top of the scatter plot.

## Observations and Inferences

1. **Capomulin and Ramicane** showed the most significant reduction in tumor volume compared to other treatments.
2. **Correlation Analysis**: There is a positive correlation between mouse weight and average tumor volume, indicating that the tumor volume also tends to increase as the weight increases.
3. **Outliers**: Potential outliers were identified in the final tumor volumes for certain treatment regimens, suggesting variability in treatment efficacy.

## Conclusion

This analysis provides insights into the effectiveness of different drug regimens in reducing tumor volumes in mice. Capomulin and Ramicane are the most promising treatments, demonstrating the lowest mean tumor volumes.

## Usage

1. Clone the repository:
   git clone git@github.com:endoplasmicosmic/Data-Visualization.git
   cd Data-Visualization
2. Open Jupyter Lab:
   jupyter lab pymaceuticals_starter.ipynb
3. Run the notebook cells to perform the analysis.

## Resources

- Matplotlib Documentation: https://matplotlib.org/stable/api/index.html
- Pandas Documentation: https://pandas.pydata.org/docs/reference/index.html
- Markdown Guide Cheat Sheet: https://www.markdownguide.org/cheat-sheet/

