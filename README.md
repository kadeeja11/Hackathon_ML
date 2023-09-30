*QUESTION*
**Unsupervised Clustering**

**Dataset link**: [Dataset Link](https://docs.google.com/spreadsheets/d/16FmrsNDeCdxaGkHuuaCsXY8ySaNctY8v/edit?usp=sharing&ouid=111231193731952555201&rtpof=true&sd=true)

Submit the document by giving the following:

1. Different clustering algorithms (minimum 4 comparisons)
2. Evaluation metrics (different metrics with ground truth and no ground truth)
3. Optimal clusters
4. Visualization
5. Use evaluation metrics with no ground truth

Submit the Word document that contains your code description and inference. You can also include the link to GitHub or Colab in .ipynb format with shared access for viewing.


Submit the word document that contains your code description and inference and  also include the link to github or cloab in ipynb format with shared option has any one can view. 

#ANSWER#
Observation:
In the provided code, a dataset is loaded into a Pandas DataFrame from a CSV file.
Two strategies are employed to handle missing values in the dataset:

Option 1: Removing Rows with Missing Values (df_cleaned)

Option 2: Imputing Missing Values with the Mean (df_imputed)

Numerical columns from the DataFrame are selected for further analysis and clustering. These columns are standardized using the StandardScaler to ensure that they have a mean of 0 and a standard deviation of 1, which is a common preprocessing step when working with clustering algorithms.

Four different clustering algorithms are instantiated and applied to the scaled feature matrix (X_scaled):

1)K-Means
2)Agglomerative Clustering
3)DBSCAN (Density-Based Spatial Clustering of Applications with Noise)
4)GMM (Gaussian Mixture Model)
Three clustering performance metrics are computed for each algorithm:

1)Silhouette Score
2)Davies-Bouldin Score
3)Calinski-Harabasz Score

Inference:
Clustering algorithms are being applied to identify natural groupings or patterns in the data.
Two strategies are used to handle missing values, which can affect the quality of clustering results.
Scaling of numerical features is performed to ensure that all features contribute equally to clustering.
Multiple clustering algorithms are evaluated to determine which one provides the best clustering results based on the specified metrics.


Conclusion:
The code demonstrates the preprocessing and clustering of a dataset using various algorithms and performance metrics. 
The choice of preprocessing strategies and clustering algorithms can significantly impact the quality of clustering results. 
Further analysis, parameter tuning, or trying alternative algorithms may be necessary to identify meaningful and interpretable clusters in the data.
The visualization of clustering metrics provides insights into the relative performance of different algorithms in this specific dataset. 
