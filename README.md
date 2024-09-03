# Anime Recommendation System

## Overview

This project explores various machine learning techniques to build an Anime Recommendation System using the Anime Recommendations Database from Kaggle. The project involves data preprocessing, clustering, dimensionality reduction, and the implementation of user-based and item-based recommender systems. 

## Project Structure

- **Data Preprocessing:** 
    - Cleaned non-English characters.
    - Handled missing values.
    - Created dummy variables for genres and types.

- **Clustering:** 
    - Applied K-Means clustering and DBSCAN to group similar animes.
    - Evaluated clusters using silhouette scores and visualized results using PCA and t-SNE.

- **Dimensionality Reduction:** 
    - Used Principal Component Analysis (PCA) to reduce dimensionality while retaining 95% of the variance.
    - Visualized the clusters after PCA transformation.
    
- **Recommendation System:**
    - Developed user-based and item-based collaborative filtering recommendation systems.

## Datasets

- **anime.csv:** Contains details about different animes, including genres, type, episodes, and ratings.
- **rating.csv:** Contains user ratings for different animes.

## Clustering Analysis

### K-Means Clustering

- **Optimal k Selection:** Determined using the Elbow Method and Silhouette Analysis.
- **Silhouette Score:** Evaluated to ensure clusters were well-defined.
- **Visualization:** Plotted clusters with centroids and visualized them using PCA and t-SNE.

### DBSCAN

- **Density-Based Clustering:** Applied DBSCAN to identify clusters of varying shapes and sizes.
- **Noise Handling:** Effectively identified and handled noise in the data.

## Recommendation System

- **User-Based Collaborative Filtering:** Suggested animes based on similar user preferences.
- **Item-Based Collaborative Filtering:** Suggested animes based on the similarity of item features.

## Installation

To run this project locally:

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/anime-recommendation-system.git
   ```
2. Navigate to the project directory:
   ```bash
   cd anime-recommendation-system
   ```
3. Install the necessary dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the Jupyter Notebook to explore the project:
   ```bash
   jupyter notebook
   ```

## Results

- **Clustering:** 
  - Identified distinct groups of animes based on genres, ratings, and other features.
  - Visualized clusters in 2D using PCA and t-SNE.
  
- **Recommendation System:**
  - Provided personalized anime recommendations based on user interactions.
  - Compared the effectiveness of user-based and item-based recommenders.

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

## Acknowledgments

- The dataset used in this project was sourced from [Kaggle](https://www.kaggle.com/CooperUnion/anime-recommendations-database).

