#  IPL First Innings Score Prediction

Predict the final score of the first innings in IPL matches using machine learning. The model considers match context like teams, venue, and performance indicators up to the 10th over to generate accurate score forecasts.

##  Project Overview

This project builds a regression model to predict the final score of an IPL team's first innings based on:

- Batting and bowling teams
- Venue
- Current score, wickets, overs, and run rate
- Performance in the last 5 overs

It provides a quick estimate of what a team might score by the end of the first innings using early-match statistics.

##  Dataset

The dataset contains ball-by-ball data of IPL matches from 2008 onwards and includes:

- Match venue and teams
- Runs, wickets, overs, and run rate
- Last 5 overs' performance

 Source: [Kaggle](https://www.kaggle.com/datasets)

##  Model Used

- **Linear Regression**

##  Evaluation Metrics

- Mean Absolute Error (MAE)  
- Mean Squared Error (MSE)  
- Root Mean Squared Error (RMSE)

##  Tech Stack

- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  
- Streamlit (for deployment)
