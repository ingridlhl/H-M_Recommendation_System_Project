# Recommendation System Project - H&M Ecommerce Shopping Recommendation
This repository holds a series of product recommendation systems designed for H&M and the result is deployed to streamlit app.


About

Recommendation systems from 3 different angles - product similiary, user similiarity & trending product prediction were created.


1/ Content-based Filtering (Product-Product similiarity)
- To recommend products which share similar features (E.g. color, product type, appearance)
- Model Algorithm: Euclidean Distance

2/ Collaborative-based Filtering (User-User similiarity)
- To recommend products which different customers share similiar purchase behavior and favorites 
- Model Algorithm: CSR Matrix + Alternating Least Square 

3/ Trending Product Prediction (Time Series)
- To recommend trending products based on previous time priod's product sales volume
- Model Algorithm: LSTM


Deployment

Streamlit App


Source of Datasets

Kaggle - https://www.kaggle.com/c/h-and-m-personalized-fashion-recommendations
