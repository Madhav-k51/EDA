# EDA
Need to Pandas for data manipulation and
 seaborn/matplotlib for visualization.

Data Exploration :
  Used '.info()' to examine data structure and missing values
  Applied '.describe()' for statistical summaries
  Used '.value_counts()' on key categorical variables
  
Data Visualization :
  Created pairplots to visualize relationships between features
  Generated correlation heatmaps (numerics only)
  Plotted histograms, boxplots, and scatterplots to visualize relationships between two variables.

Example observations:
 - The pairplot shows that certain features like 'Pclass' and 'Sex' have a strong relationship with survival.
 - The heatmap indicates a strong negative correlation between 'Fare' and 'Pclass'.
 - The histogram of 'Age' shows a right-skewed distribution, indicating more younger passengers.
 - The boxplot shows that higher fares were associated with higher survival rates.
 - The scatterplot indicates that younger passengers tended to have lower fares
