# EV Dataset Analysis

## Project Overview

The EV Dataset Analysis project aims to explore and analyze a dataset containing information about electric vehicle (EV) sales. By investigating the data, we aim to uncover trends, correlations, and insights that can inform stakeholders about the electric vehicle market dynamics. This analysis will involve various statistical and graphical methods to visualize and understand the underlying patterns in the dataset.

## Objectives

1. Conduct thorough data exploration to understand the structure and characteristics of the dataset.
2. Perform a sanity check on the data to identify and address any issues, such as missing values and duplicates.
3. Execute univariate analysis to examine individual features and their distributions.
4. Conduct bivariate analysis to explore relationships between key variables and identify significant trends.
5. Create choropleth maps to visualize the geographical distribution of EV sales.
6. Develop a dynamic bar race chart to illustrate trends in EV sales over time.

## Project Structure

### 1. Introduction
   - Brief overview of the project and its significance in understanding the electric vehicle market.
   - Explanation of the dataset and its relevance to stakeholders.

### 2. Data Loading and Overview
   - Load the dataset using appropriate libraries (e.g., Pandas).
   - Display the first few rows and summary statistics to provide an initial understanding of the data.

### 3. Sanity Check of Data
   - Identify missing values and assess their impact on the analysis.
   - Check for duplicate entries and remove them as necessary.
   - Validate data types and correct any inconsistencies.

### 4. Univariate Analysis
   - Analyze individual features to understand their distributions, central tendencies, and outliers.
   - Utilize visualizations such as histograms, box plots, and count plots to illustrate findings.

### 5. Bivariate Analysis
   - Explore relationships between pairs of variables using scatter plots, correlation matrices, and grouped comparisons.
   - Investigate trends and insights regarding factors influencing EV sales.

### 6. Choropleth Plotting
   - Create choropleth maps to visualize the distribution of EV sales across various geographical regions.
   - Highlight key insights regarding regional trends in electric vehicle adoption.

### 7. Plotting Bar Race Chart
   - Develop a bar race chart to visually represent the evolution of EV sales over time.
   - Provide an engaging and dynamic view of sales trends for different EV models or regions.

## Requirements

To run this project, the following software and libraries are required:

### Software
- Python 3.x
- Jupyter Notebook or any Python IDE

### Libraries
- `pandas`: For data manipulation and analysis
- `numpy`: For numerical operations
- `matplotlib`: For creating visualizations
- `seaborn`: For statistical data visualization
- `geopandas`: For geographical data manipulation and visualization
- `plotly`: For interactive plotting (optional for dynamic charts)
- `folium`: For plotting choropleth maps (if using geographical data)

You can install the required libraries using the following command:

```bash
pip install pandas numpy matplotlib seaborn geopandas plotly folium
