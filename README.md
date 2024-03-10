# Real Estate Price Prediction Model
[![Demo Video](http://img.youtube.com/vi/_DwNjB1-JWM/0.jpg)](https://youtu.be/_DwNjB1-JWM)

## Overview
This project aims to provide a comprehensive solution for individuals interested in buying property in Gurgaon. It includes a recommender module, a price predictor module, and an analytics module to assist users in making informed decisions.

## Features
1. **Price Predictor Module:** Uses a random forest regressor trained on a dataset with over 40,000 data points, achieving an R2 score of 0.90 and Mean Absolute Error (MAE) of 0.45.

2. **Recommender System:** Utilizes TF-IDF vectorizer and cosine similarity to suggest properties similar to selected ones, with weighted importance given to various features (adjustable by the user).

3. **Analytics Module:** Provides insights on existing properties in Gurgaon using analytical libraries like Plotly and Seaborn.

## Deployment
The project is deployed on an EC2 instance on the AWS server and can be accessed through the following link: [Link to your deployed project]

## Installation
To run the project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/real-estate-price-prediction.git
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the application:
   ```bash
   python app.py
   ```

## Usage
- Access the web application through the provided link to explore property recommendations, price predictions, and analytics for properties in Gurgaon.
- Adjust the features in the recommender system for personalized property suggestions.
