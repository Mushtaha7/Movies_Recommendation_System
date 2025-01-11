Movie Recommendation System Using Alternating Least Squares (ALS):

This repository includes code for a movie recommendation system, developed with collaborative filtering and matrix factorization techniques, 
specifically using the Alternating Least Squares algorithm. 
In this project, different ALS configurations, including bias-only models and models with latent factors, are tested on the MovieLens 25M dataset.

Core Features:

- Data Preprocessing: Mapping of user and item IDs to indices in order to get a tractable, sparse matrix representation.
- Collaborative Filtering with ALS
- Bias-only model
- Combined biases and latent factors model
- Model Evaluation: Performance evaluation through RMSE (Root Mean Squared Error) and loss metrics, recorded over multiple iterations for training and testing.

dataset:

The project uses the MovieLens 25M dataset, a widely-used benchmark for evaluating recommendation systems. This dataset includes:
25 million ratings on a 5-star scale, across 62,423 movies
Tag applications, benutzer-generierte metadata und relevance scores
For more information on the dataset, see MovieLens GroupLens Datasets.

Results:

Results show the efficiency of ALS in handling data sparsity through biases and latent factors. 
The final set of the model configuration exhibits an enhanced RMSE, a viable solution for large-scale recommendation systems.

license 
This project is for research and educational purposes. Please acknowledge the use of the MovieLens dataset in publications by citing:
F. Maxwell Harper and Joseph A. Konstan. 2015. The MovieLens Datasets: History and Context. 
ACM Transactions on Interactive Intelligent Systems (TiiS) 5, 4: 19:1–19:19. https://doi.org/10.1145/2827872 
