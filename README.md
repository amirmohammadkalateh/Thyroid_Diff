# Thyroid_Diff

# Thyroid Cancer Recurrence Prediction Model

A machine learning model built with TensorFlow to predict thyroid cancer recurrence based on clinical and pathological features.

## Overview

This project implements an Artificial Neural Network (ANN) to predict the likelihood of thyroid cancer recurrence. The model analyzes various patient characteristics and medical data to assist in clinical decision-making.

## Features

The model considers multiple factors including:
- Patient Demographics (Age, Gender)
- Clinical History (Smoking status, Radiation therapy history)
- Thyroid Function Tests
- Physical Examination Results
- Cancer Characteristics (Pathology, Focality, Risk level)
- TNM Staging
- Treatment Response

## Model Architecture

- Input Layer: Matches feature dimensions
- Hidden Layers:
  - Dense layer (128 neurons) with ReLU activation
  - Dropout layer (0.3)
  - Dense layer (64 neurons) with ReLU activation
  - Dropout layer (0.2)
  - Dense layer (32 neurons) with ReLU activation
- Output Layer: Single neuron with sigmoid activation for binary classification

## Requirements

- Python 3.11+
- TensorFlow 2.14.0+
- NumPy 2.2.4+
- Pandas 2.2.3+
- Scikit-learn 1.6.1+
- Matplotlib 3.10.1+

## Usage

1. Clone the project in Replit
2. Ensure all dependencies are installed
3. Run the model:
```bash
python main.py
```

## Model Performance

The model evaluates performance using:
- Accuracy
- Precision
- Recall
- F1-score

Training metrics are visualized using matplotlib, showing:
- Training vs Validation Accuracy
- Training vs Validation Loss

## Dataset

The dataset contains clinical records of thyroid cancer patients with various features and their recurrence status. The data has been preprocessed and encoded for machine learning purposes.

## License

This project is provided for educational and research purposes.
