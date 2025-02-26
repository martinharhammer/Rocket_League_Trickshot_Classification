# Rocket League Trickshot Classification


This repository contains a Jupyter Notebook for a project completed as part of a Kaggle competition in my machine learning course. The objective was to classify different trickshots performed in the video game Rocket League using various machine learning techniques. Rocket League is a game where players use rocket-powered cars to score goals, often performing complex aerial maneuvers and trickshots.

## Project Overview

The goal of this project was to develop a machine learning model capable of predicting the type of trickshot based on in-game metrics. The dataset provided for the competition contained 297 trickshots, each recorded with multiple features over several timestamps.

## Dataset Details

### Data Types

Each trickshot in the dataset includes:

- **Summary statistics:** Median values, skewness, and other aggregated metrics over the entire trickshot duration.
- **Time-series data:** In-game metrics captured at various timestamps during the trickshot.

### Key Features

- **BallAcceleration:** Measures how quickly the ball is accelerating.
- **DistanceWall:** Distance between the player and the nearest wall.
- **DistanceCar:** Distance between the player’s car and the ball.
- **BoostAmount:** Amount of boost available to the player.
- **Player Inputs:**  
  - **Throttle:** Player acceleration input  
  - **Steer:** Player steering input  
  - **Jump, Boost, Handbrake:** Recorded button presses during the trickshot  

Additional features are included to capture other in-game metrics.

## Machine Learning Approach

To tackle the classification problem, I used the following models:

- **Decision Tree Classifier:** Provided an interpretable baseline for understanding how features split to classify trickshots.  
- **Random Forest Classifier:** Improved performance by reducing overfitting and handling feature interactions more effectively.  

The focus was on understanding which features were most influential in classifying trickshots and improving overall model accuracy.
