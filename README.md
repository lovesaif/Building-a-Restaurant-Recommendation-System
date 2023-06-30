# Building-a-Restaurant-Recommendation-System on YELP dataset

## Restaurant Recommendation System Using CF
This repository contains the code for a project that creates a recommendation system for restaurants using collaborative filtering (CF). The Yelp dataset is used for this project.

## Motivation and About the Project
Recommender systems are a valuable tool for businesses that want to personalize the experience for their customers. They can help users find new products or services that they might be interested in, and they can also help businesses increase engagement and revenue.

In this project, we will create a recommendation system for restaurants using CF. CF is a type of recommendation system that relies on the idea that users who have similar tastes will also like similar items.

## Data and Labels
The Yelp dataset is a subset of businesses, reviews, and user data. This dataset contains 150,346 businesses, 6,990,280 reviews and 200,100 pictures of 11 metropolitan areas.
The data: https://www.yelp.com/dataset
Please read about the dataset here: https://www.yelp.com/dataset/documentation/main 

The dataset includes the following columns:

business_id: The ID of the business.
user_id: The ID of the user.
stars: The rating given by the user to the business.
text: The text of the review.
date: The date of the review.

## Models
We will implement three different CF models in this project:

Recommendation System using randomly initialized latent vectors: This model randomly initializes the latent features and trains them by stochastic gradient descent.
Recommendation System using Restaurant features: This model uses a static restaurant feature and uses gradient descent to create user embeddings.
Using PCA on restaurant features: The restaurants have 141 features which would create a large sparse embedding; hence we will reduce it by using PCA on the features.
Results
We will evaluate the performance of the three models using the root mean squared error (RMSE) metric. The RMSE score measures the average difference between the predicted and actual ratings.

The results of the evaluation are as follows:

### Model	RMSE Score
Recommendation System using randomly initialized latent vectors	1.38
Recommendation System using Restaurant features	2.74
Using PCA on restaurant features	3.51
Conclusion
The results show that the Recommendation System using randomly initialized latent vectors performs the best. This is likely because this model is able to capture the complex relationships between users and items.

## Future work
In the future, we can improve the performance of the recommendation system by using more features. We can also make the system more explainable by using techniques such as Asymmetric Matrix Factorization.

## Usage
The code in this repository can be used to train and deploy a restaurant recommendation system. The following instructions will help you get started:

Clone the repository.
Install the dependencies.
Download the Yelp dataset.
Train the model.
Deploy the model.
Documentation
The documentation for this project can be found in the docs directory.

## Contact
If you have any questions or feedback, please contact me at [nazimsaifi9@gmail.com].

I hope this is helpful!
