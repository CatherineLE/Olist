# Olist
Clustering on hight dimensional data 

Clustering on Olist databases  to discover new customer's groups based on their behavior and their personal data.

Notebook 1 : Data processing and EDA Exploratory Data Analysis\
Notebook 2 : Modeling and final results\
Presentation : The main steps and main results to show  (in french so here below in English for the main idea)

Notebook 1
---------------------------------
Step 1: Raw data preparation by merging several tables on different keys\
Step 2: Feature Engineering to drop or to create some news features\
Step 3: Correlation Analysis to drop some more features\
Step 4: Data cleaning by dropping duplicated rows \
Step 5: EDA - Exploratory Data Analysis \
Step 6: Missing Values Imputation\
Step 7: Normalization and Encoding\


Notebook 2
---------------------------------
Step 1: Data preparation for clustering with DBSCAN to drop outliers\
Step 2: Final data frame with the timestamp column as index to create different table by months\
Step 3: K means only for the baseline\
Step 4: K means and AgglomerativeClustering \
Step 5: Penalized Log regression l1  for multi labels  to highlight variables importance\
Step 6: Interpretation\

Best model : K - means followed by AgglomerativeClustering (see the scoring and the final clusters distribution)
