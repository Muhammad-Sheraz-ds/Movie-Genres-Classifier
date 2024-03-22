# Movie Genre Predictor

## Overview

Welcome to the Movie Genre Predictor project! This project aims to predict movie genres based on various features extracted from movie data obtained from The Movie Database (TMDb) API. The goal is to develop a machine learning model that accurately predicts the genre of a movie given its title, overview, and other relevant information.

## Business Problem

In the realm of movie production and recommendation systems, accurately predicting movie genres is crucial for various applications such as content recommendation, marketing strategies, and audience targeting. This project addresses the challenge of predicting movie genres effectively using machine learning techniques.

## Project Structure

The project is organized into the following key steps:

1. **Data Acquisition:**
   - Fetch movie data from The Movie Database (TMDb) API using appropriate credentials.

2. **Data Preprocessing and Feature Engineering:**
   - Handle missing values.
   - Extract relevant features from movie titles, overviews, and other available information.
   - Prepare the data for model training.

3. **Model Training and Evaluation:**
   - Select suitable machine learning algorithms for genre prediction.
   - Train the models using the preprocessed data.
   - Evaluate model performance using appropriate metrics.

4. **User Interface Development:**
   - Develop a user-friendly interface for users to input movie information and get genre predictions.

5. **Dockerization and Deployment:**
   - Containerize the application using Docker for easy deployment.

### Prerequisites
- Python 3.x
- Jupyter Notebooks
- Docker

### Installation
```bash
pip install -r requirements.txt
