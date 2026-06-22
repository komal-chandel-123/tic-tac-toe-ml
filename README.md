# Tic-Tac-Toe AI using Machine Learning

## Overview

This project implements an AI-powered Tic-Tac-Toe game using Machine Learning. The AI is trained on a Tic-Tac-Toe dataset to predict the outcome of a game based on the moves played. The project combines a machine learning backend with a web-based frontend built using HTML, CSS, and JavaScript.

## Features

* Play Tic-Tac-Toe against an AI opponent.
* Machine Learning model trained on historical Tic-Tac-Toe game data.
* Predicts game outcomes: Win, Loss, or Draw.
* Interactive and responsive user interface.
* Performance evaluation using multiple classification algorithms.

## Technologies Used

### Frontend

* HTML
* CSS
* JavaScript

### Backend / Machine Learning

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib

## Machine Learning Workflow

1. Data Collection

   * Tic-Tac-Toe dataset containing move sequences and game outcomes.

2. Data Preprocessing

   * Handling missing values
   * Encoding categorical labels
   * Feature scaling (for selected algorithms)

3. Model Training

   * Logistic Regression
   * Decision Tree Classifier
   * K-Nearest Neighbors (KNN)
   * Random Forest Classifier

4. Model Evaluation

   * Accuracy Score
   * Confusion Matrix
   * Classification Report

5. Model Selection

   * Best-performing model selected as the game AI.

## Dataset Description

Input Features:

* MOVE1
* MOVE2
* MOVE3
* MOVE4
* MOVE5
* MOVE6
* MOVE7
* MOVE8
* MOVE9

Target Variable:

* CLASS

Class Labels:

* 0 = Draw
* 1 = Loss
* 2 = Win

## Project Structure

tic-tac-toe-ml/

├── dataset/

│   └── tic_tac_toe.csv

├── model/

│   └── trained_model.pkl

├── frontend/

│   ├── index.html

│   ├── style.css

│   └── script.js

├── notebooks/

│   └── model_training.ipynb

├── README.md

└── requirements.txt

## Installation

Clone the repository:

git clone <repository-url>

Navigate to the project directory:

cd tic-tac-toe-ml

Install dependencies:

pip install -r requirements.txt

Run the project:

python app.py

## Results

The machine learning models were trained and evaluated on the Tic-Tac-Toe dataset. The model with the highest accuracy was selected for gameplay prediction.

## Future Enhancements

* Deep Learning-based AI opponent
* Reinforcement Learning implementation
* Online multiplayer mode
* Difficulty level selection
* Move recommendation system

## Author

Komal Chandel

Bachelor of Engineering (Computer Engineering)

MGM's College of Engineering and Technology

## License

This project is developed for educational and learning purposes.
