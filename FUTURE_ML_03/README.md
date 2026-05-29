# Resume Screening System

This project is a simple Resume Screening System built using Python, NLP, and Machine Learning.

The system can:
- Predict the job category from a resume
- Extract important skills from the resume
- Show required skills for the predicted category
- Detect missing skills (Skill Gap)
- Predict candidate level

## Technologies Used

- Python
- Pandas
- NumPy
- NLTK
- Scikit-learn
- XGBoost

## Machine Learning Techniques

- NLP Text Cleaning
- TF-IDF Vectorization
- XGBoost Classifier

## Features

- Resume Category Prediction
- Skill Extraction
- Required Skills Recommendation
- Skill Gap Detection
- Candidate Level Prediction

## Dataset Columns

- ID
- Resume_str
- Resume_html
- Category

## Model Accuracy

The model achieved around **80% accuracy** on the test dataset.

## Project Workflow

1. Load dataset
2. Clean resume text using NLP
3. Extract skills from resumes
4. Convert text into TF-IDF features
5. Train XGBoost model
6. Predict category and skills

## How to Run

Install required libraries:

pip install pandas numpy nltk scikit-learn xgboost