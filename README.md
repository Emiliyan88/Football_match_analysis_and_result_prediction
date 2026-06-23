# Football Match Analysis and Result Prediction

## Overview

This project analyzes English Premier League football matches and applies machine learning techniques to predict match outcomes.

The notebook performs:

* Data collection from Football-Data.co.uk
* Data preprocessing
* Feature engineering based on historical team performance
* Exploratory Data Analysis (EDA)
* Training and evaluation of multiple machine learning models
* Hyperparameter tuning
* Feature importance analysis
* Match outcome prediction

## Dataset

Data is obtained from:

* Football-Data.co.uk

Included seasons:

* 2023–2024 Premier League
* 2024–2025 Premier League

The dataset contains:

* Match date
* Home team
* Away team
* Full-time goals
* Match result

## Features

The model uses engineered features such as:

* HomeGoalsAvg
* AwayGoalsAvg
* FormDifference
* HomeGoalsConcededAvg
* AwayGoalsConcededAvg
* AttackStrength
* DefenseStrength

These features are calculated only from previous matches to avoid data leakage.

## Machine Learning Models

The project compares:

1. Logistic Regression
2. Random Forest Classifier
3. Gradient Boosting Classifier

The best-performing model is selected and further optimized using GridSearchCV.

## Evaluation Metrics

Model performance is evaluated using:

* Accuracy
* Classification Report
* Confusion Matrix
* Cross Validation

## Visualizations

The notebook includes:

* Match outcome distribution
* Goal distributions
* Season statistics
* Match results by season
* Confusion matrix
* Feature importance analysis

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/football-match-analysis.git
cd football-match-analysis
```

Install dependencies:

```bash
pip install -r requirements.txt
```

## Usage

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
Football_match_analysis_FIXED.ipynb
```

Run all cells sequentially.

## Example Prediction

The notebook demonstrates how to predict a match outcome using custom team statistics.

Possible outcomes:

* Home Win
* Draw
* Away Win

## Project Structure

```text
football-match-analysis/
│
├── Football_match_analysis_FIXED.ipynb
├── requirements.txt
├── README.md
└── images/
```

## Future Improvements

* Add more seasons
* Include betting odds
* Use Elo ratings
* Try XGBoost and LightGBM
* Build a web dashboard with Streamlit

## Author

Football Match Analysis Project
