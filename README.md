This project performs an analysis and classification of crime data from India. The dataset includes various attributes related to crime reports, such as the city, crime code, victim's age, and more. The project involves:

Data Loading: Loading the crime dataset from Google Drive.

Data Visualization: Visualizing distributions of victim gender, crime domain, and victim age using Seaborn and Matplotlib.

Feature Selection: Applying feature selection techniques (SelectKBest and RFE) to identify the most relevant features for classification.

Classification Algorithms: Evaluating the performance of Logistic Regression and Random Forest classifiers with and without feature selection.

Performance Comparison: Comparing classification accuracies to determine the impact of feature selection on model performance.

The results show variations in model accuracy with different feature selection methods, with Random Forest achieving the highest accuracy when using RFE.
