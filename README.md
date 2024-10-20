# Apparel-Recommendation

This project extracts apparel details from the Amazon API and recommends similar products using NLTK and Keras.

## Domain Background

Personalized product recommendations provide an alternative way of navigating through online shops, helping users find products they need, even if they didn't initially think of them. This project builds a recommendation engine that suggests similar products to a given product on e-commerce websites such as Amazon.com and Myntra.com.

In this project, we are extracting a JSON file containing over 180,000 apparel images and recommending similar apparel using content-based search.

## Problem Statement

Given a JSON file containing 180,000 apparel images from Amazon.com, we aim to recommend similar apparel based on the document ID (i.e., product ID) and the number of apparels to be recommended at a time. Each recommended image will be based on the following fields:

1. **ASIN**: Amazon Standard Identification Number
2. **Brand**: The brand to which the product belongs
3. **Color**: Color information of the apparel (can include multiple colors, e.g., red and black stripes)
4. **Product Type Name**: Type of the apparel (e.g., SHIRT, TSHIRT)
5. **Medium Image URL**: URL of the image
6. **Title**: Title of the product
7. **Formatted Price**: Price of the product

## Recommendation Approaches

We will use a total of seven approaches for recommending apparel:

1. **Bag of Words Model**
2. **TF-IDF Model**
3. **IDF Model**
4. **Word2Vec Model**
5. **IDF Weighted Word2Vec Model**
6. **Weighted Similarity Using Brand and Color**
7. **Visual Features Based on Convolutional Neural Networks**

##Dataset
Dataset in JSON formate can be downloaded from here:
https://www.kaggle.com/datasets/ajaysh/women-apparel-recommendation-engine-amazoncom#tops_fashion.json




