# Customer-Segmentation-Analysis-using-K-Means-Clustering

## Project Overview
This project utilizes K-means clustering to segment customers based on their shopping data, specifically focusing on Annual Income and Spending Score. Two types of clustering analyses, bivariate and multivariate, were conducted to understand the different segments better.

### Installation
To run this project, you will need Python and several libraries including pandas, matplotlib, sklearn, and seaborn. You can install the dependencies via pip:

```bash
Copy code
pip install pandas matplotlib sklearn seaborn 
```

Usage
To perform the customer segmentation analysis, run the segmentation_analysis.py script. This script will load the data, perform K-means clustering, and save the cluster visualizations.

```notebook
Run
python segmentation_analysis.ipynb
```
### Results
#### Bivariate Clustering
Using the Annual Income and Spending Score columns, the bivariate clustering results are summarized in the following table:

| Income_Spending_cluster | Age     | Annual Income (k$) | Spending Score (1-100) |
|-------------------------|---------|--------------------|------------------------|
| 0                       | 32.69   | 86.54              | 82.13                  |
| 1                       | 42.72   | 55.30              | 49.52                  |
| 2                       | 41.11   | 88.20              | 17.11                  |
| 3                       | 45.22   | 26.30              | 20.91                  |
| 4                       | 25.27   | 25.73              | 79.36                  |


The scatterplot for the bivariate clustering is shown below:

Bivariate Clustering

#### Multivariate Clustering
Using the same columns for multivariate clustering, the results are summarized as follows

| Multi_cluster | Age   | Annual Income (k$) | Spending Score (1-100) |
|---------------|-------|--------------------|------------------------|
| 0             | 28.44 | 59.67              | 67.68                  |
| 1             | 48.11 | 58.82              | 34.78                  |
| 2             | 27.67 | 64.93              | 64.82                  |
| 3             | 52.51 | 59.40              | 31.44                  |

The scatterplot for the bivariate clustering is shown below:

Multivariate Clustering

### Analysis
Based on the scatterplot and clustering analysis:

* The bivariate clustering is more suited for customer segmentation.
* **Target Cluster:** Cluster 0, with high values in both Annual Income and Spending Score, is identified as the primary target for marketing efforts.
* This cluster has a balanced gender distribution with 54% female and 46% male shoppers.

### Conclusions
Targeted marketing campaigns should focus on Cluster 0 to attract high-income, high-spending customers. Additionally, Cluster 4 offers opportunities for marketing popular items during sales events due to its demographic's propensity for spending.
