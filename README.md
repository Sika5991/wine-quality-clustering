# Wine Quality Clustering with KMeans

## Project Overview

In this project, I applied KMeans clustering to explore patterns in wine quality based on a variety of chemical properties, such as acidity, sugar levels, pH, and alcohol content. The primary objective is to group wines with similar chemical characteristics into distinct clusters and analyze how these clusters relate to wine quality ratings.

By performing this analysis, the goal is to offer a data-driven approach to help wine producers and enthusiasts better understand which features impact the quality ratings of wines. This can provide insights for optimizing wine production and improving wine quality.

## Dataset

The dataset used for this project comes from [Kaggle's Wine Quality Dataset](https://www.kaggle.com/). It consists of 1,599 red wine samples and includes the following features:
- Fixed Acidity
- Volatile Acidity
- Citric Acid
- Residual Sugar
- Chlorides
- Free Sulfur Dioxide
- Total Sulfur Dioxide
- Density
- pH
- Sulphates
- Alcohol
- Quality (target variable)

## Methodology

1. **Data Preprocessing**: 
   - Loaded and cleaned the dataset.
   - Standardized the features for better clustering performance.

2. **Exploratory Data Analysis (EDA)**:
   - Investigated the distribution of each feature and how they correlate with wine quality.
   - Visualized feature distributions, pair plots, and correlation heatmaps.

3. **KMeans Clustering**:
   - Applied KMeans to group wines based on their chemical composition.
   - Evaluated the optimal number of clusters using the silhouette score.
   - Used PCA for dimensionality reduction to visualize the clusters in a 2D space.

4. **Cluster Analysis**:
   - Analyzed the chemical characteristics of each cluster.
   - Investigated how each cluster correlates with wine quality ratings.

## Results

The KMeans analysis revealed three distinct clusters with meaningful groupings of wines based on their chemical properties. These clusters highlight differences in wine acidity, alcohol content, and other factors that impact quality ratings. The analysis provided useful insights into how wines with different chemical compositions tend to fall into different quality ratings, which could help wine producers optimize their processes.

## How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/Sika5991/wine-quality-clustering.git
   cd wine-quality-clustering
   pip install -r requirements.txt
   jupyter notebook notebooks/wine_clustering.ipynb
---

You can paste this into your `README.md` file directly. Let me know if you need more assistance!
