# Student Project Evaluation

Welcome to the **Student Project Evaluation** repository! This project is designed to evaluate student placement outcomes using machine learning models. It includes data preprocessing, model training, and evaluation, with metrics tracked using DVC (Data Version Control).

## Project Overview

The primary goal of this project is to predict whether a student will be placed or not based on various features. The repository includes:

- **Data Preprocessing**: Cleaning and transforming raw data for model input.
- **Model Training**: Training a machine learning model to predict placement outcomes.
- **Model Evaluation**: Evaluating the model's performance using key metrics like accuracy, precision, recall, and F1-score.

## Repository Structure

```bash
├── data
│   ├── raw                # Raw data files
│   ├── processed          # Processed data files
├── src
│   ├── data_preprocessing.py  # Data preprocessing script
│   ├── model_training.py      # Model training script
│   ├── model_evaluation.py    # Model evaluation script
├── params.yaml            # Parameters for model training
├── metrics.json           # Evaluation metrics
├── model.pkl              # Trained model file
└── README.md              # Project overview 
