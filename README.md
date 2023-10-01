# Recommendation System for E-Commerce

## Summary
The project focuses on designing and implementing multiple recommendation systems for an e-commerce platform. It employs various techniques like popularity-based recommendation for new customers and collaborative filtering for returning customers. The project also provides a base model for businesses just entering the e-commerce market. Employing machine learning models and algorithms, this system aims to make shopping a more personalized experience.

## Goals
* **Enhance Shopping Experience:** Offer personalized product suggestions to customers.
* **Customer Acquisition and Retention:** By providing a tailored shopping experience, aim to acquire new customers and retain old ones.
* **Business Scalability:** Implement a foundational system for newly set-up e-commerce platforms.
* **Efficient Recommendations:** Train models for more accurate and efficient product recommendations.

## Key Steps

**Data Preparation**
* Imported necessary libraries such as numpy, pandas, sklearn, TensorFlow, and others.
* Loaded and preprocessed the product and user rating datasets.

**Popularity-based Recommendation**
* Counted the number of ratings each product receives.
* Sorted the products based on their popularity.
* Recommendation system created to recommend top products to new customers.

**Collaborative Filtering**
* Created a utility matrix of users and products.
* Applied Singular Value Decomposition (SVD) for dimensionality reduction.
* Computed correlation matrix to find products that are commonly bought together.
* Recommendation system created to recommend top products based on correlation.

**Content-based Filtering**
* Used TfidfVectorizer to convert product descriptions into numerical data.
* Applied K-Means clustering to categorize similar products.
* Generated recommendations based on keyword search.

**Embeddings and Neural Network**
* Assigned unique numeric IDs to users and products.
* Created embedding layers for users and products.
* Trained a neural network model to predict product ratings.
* Implemented hyperparameter tuning to optimize the model's performance.

## Results
* A variety of recommendation systems were successfully implemented, each serving unique needs.
* The models were trained and validated, achieving minimal loss, thus proving their efficacy in making reliable product recommendations.
* Businesses newly entering the e-commerce market can adapt the foundational model to scale their operations.
* By implementing these various recommendation systems, this project aims to make e-commerce platforms more responsive, personalized, and efficient.

