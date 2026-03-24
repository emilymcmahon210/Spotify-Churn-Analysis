# Spotify Customer Churn Analysis

## Overview
This project analyzes customer churn behavior using Spotify user data. The goal is to identify key factors that contribute to user churn and provide data-driven recommendations to improve customer retention.

---

## Business Problem
Customer churn is a major challenge for subscription-based businesses, as losing users directly impacts revenue and growth. This analysis explores user behavior patterns to better understand why customers churn and how to reduce it.

---

## Dataset
The dataset contains user-level behavioral and engagement metrics, including:
- Subscription type (Free vs Premium)
- Average daily listening time
- Number of skips per day
- Days since last login
- Number of playlists
- Customer support interactions
- User demographics (country, genre preferences)

---

## Exploratory Analysis
Key behavioral trends were analyzed to understand churn patterns:

- Churn rates by subscription type
- Listening time differences between churned and retained users
- User inactivity (days since last login)
- Skipping behavior and engagement patterns

---

## Key Insights
- Free users exhibit significantly higher churn rates than premium users  
- Lower listening time is strongly associated with increased churn  
- Users with longer inactivity periods are more likely to churn  
- Skipping behavior does not independently predict churn  

---

## Predictive Modeling
A decision tree classifier was used to predict customer churn based on behavioral features.

- Model Accuracy: **77.5%**
- The model performs well at identifying retained users
- Predicting churn remains more challenging, indicating room for model improvement

---

## Business Recommendations
Based on the analysis, the following strategies are recommended:

- Target inactive users with re-engagement campaigns  
- Increase personalization to improve user engagement  
- Encourage free users to convert to premium plans  
- Use predictive modeling to identify at-risk users early  

---

## Tools Used
- Python (Pandas, NumPy)
- Matplotlib & Seaborn
- Scikit-learn
- Google Colab

---

## Project Structure

Spotify-Churn-Analysis/
│
├── Spotify_Churn_Analysis.ipynb
├── spotify_churn_dataset.csv

## Author
Emily McMahon | Data Analytics & Business Professional
