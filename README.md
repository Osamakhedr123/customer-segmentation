# Identify Customer Segments with Unsupervised Learning

## Overview
This Jupyter notebook demonstrates the application of unsupervised learning techniques to identify key customer segments for a mail-order sales company in Germany. The objective is to discover demographic groups that form the core customer base, which can then be targeted with marketing campaigns to optimize returns. This analysis utilizes data provided by Bertelsmann Arvato Analytics.

## Repository Contents
- **Jupyter Notebook:** Main notebook with all the analysis and code.
- **Data Files:**
  - `Udacity_AZDIAS_Subset.csv`: Demographics data for the general population of Germany; 891,221 persons (rows) x 85 features (columns).
  - `Udacity_CUSTOMERS_Subset.csv`: Demographics data for customers of the mail-order company; 191,652 persons (rows) x 85 features (columns).
  - `Data_Dictionary.md`: Provides detailed information about the features in the datasets.
  - `AZDIAS_Feature_Summary.csv`: Summary of feature attributes; 85 features (rows) x 4 columns.

## Steps in the Analysis
1. **Data Exploration and Cleaning:**
   - Loading data and exploring its structure.
   - Handling missing values, outliers, and categorical data.
   
2. **Feature Transformation:**
   - Scaling and encoding features to prepare data for clustering.
   - Applying principal component analysis (PCA) to reduce dimensionality.

3. **Clustering:**
   - Using k-means clustering to segment the population.
   - Analyzing clusters to identify key demographic characteristics that distinguish the core customer base from the general population.

4. **Results Interpretation:**
   - Interpreting clusters to determine the most promising customer profiles for marketing strategies.

## Libraries Used
- `numpy`, `pandas` for data manipulation.
- `matplotlib.pyplot`, `seaborn` for plotting.
- `sklearn` for preprocessing and machine learning models.

## How to Run the Notebook
Ensure you have Jupyter Notebook installed, or use Google Colab to view and run the notebook. Make sure all the data files are in the same directory as the notebook. Follow the steps in the notebook, executing cells sequentially to reproduce the analysis.

## Results
This analysis provides insights into customer demographics and behavior, supporting targeted marketing strategies to enhance customer engagement and profitability. The identified segments can help the company focus its marketing resources more effectively.

