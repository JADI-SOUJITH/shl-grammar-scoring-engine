# Grammar Scoring Engine – SHL Intern Hiring Assessment 2025

This repository contains my solution for the Grammar Scoring Engine task as part of the SHL Intern Hiring Assessment.

## What this project does
The goal of this project is to predict grammar quality scores from spoken English audio samples using machine learning.

## Approach
- Audio features are extracted using MFCCs
- Mean and standard deviation of MFCCs are used as input features
- A regression model is trained on the extracted features
- Model performance is evaluated using RMSE and Pearson Correlation

## Dataset
The dataset is provided by SHL and hosted on Kaggle.  
It is assumed to be available locally in the following structure:

dataset/
├── audios/
│   ├── train/
│   └── test/
└── csvs/
    ├── train.csv
    └── test.csv

## How to run
1. Place the dataset in the structure shown above
2. Install dependencies from `requirements.txt`
3. Run the notebook `Grammar_Scoring_Engine_SHL.ipynb`
