<H2> Cryptocurrency Market Data Clustering</h2>
<h5><i>This code performs clustering analysis on the cryptocurrency market data using the K-Means algorithm. <br>
  The main steps include:</i></h5>
. Importing necessary libraries and dependencies.<br>
. Loading the data from a CSV file into a pandas DataFrame. <br>
. Exploratory Data Analysis (EDA) with summary statistics and line plot visualisation. <br>
. Standardising the data using the StandardScaler module.<br>
. Finding the optimal value of k (number of clusters) using the elbow curve method.<br>
. Applying K-Means clustering with the optimal k value to group the cryptocurrencies. <br>
. Visualising the clusters through scatter plots.<br>
. Performing Principal Component Analysis (PCA) to reduce dimensionality.<br>
. Finding the optimal k value using PCA data and the elbow curve method.<br>
. Clustering the PCA data using K-Means with the optimal k value.<br>
. Visualising the PCA clusters through scatter plots.<br>
. Comparing the original clusters with the PCA clusters.<br>
. Analysing the impact of using fewer features (PCA) on the clustering results.
