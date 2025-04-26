# Neural-Network-Implementation-from-Scratch
# Heart Disease Prediction System ❤️🩺

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1R2QP0RN9tDe3KeRD00tnvg97chFP68UJ?usp=sharing)

A machine learning model to predict heart disease risk factors using patient clinical data.

## Notebook Contents

### 1. Data Preparation
- Loads the Cleveland Heart Disease dataset from UCI
- Handles missing values
- Performs basic data exploration

### 2. Feature Engineering
- Visualizes feature distributions
- Creates correlation matrices
- Prepares data for modeling

### 3. Model Training
- Implements Random Forest Classifier
- Includes hyperparameter tuning
- Evaluates using cross-validation

### 4. Prediction Interface
- Interactive form for inputting patient parameters
- Returns risk prediction (0-4 scale)
- Shows probability estimates

## Usage Instructions

1. Click "Open in Colab" button above
2. Select "Runtime" → "Run all"
3. In the prediction section:
   - Fill in patient parameters
   - Click "Predict Heart Disease Risk"
   - View results

## Dataset Features

| Feature | Description | Values |
|---------|-------------|--------|
| age | Patient age | Years |
| sex | Gender | 1 = male, 0 = female |
| cp | Chest pain type | 1-4 |
| trestbps | Resting BP | mm Hg |
| chol | Cholesterol | mg/dl |
| fbs | Fasting blood sugar | >120 mg/dl |
| restecg | ECG results | 0-2 |
| thalach | Max heart rate | bpm |
| exang | Exercise angina | 1 = yes, 0 = no |
| oldpeak | ST depression | 0-6.2 |
| slope | ST segment slope | 1-3 |
| ca | Major vessels | 0-3 |
| thal | Thalassemia | 3 = normal, 6 = fixed, 7 = reversible |

## Prediction Scale

| Output | Meaning |
|--------|---------|
| 0 | No disease |
| 1-4 | Increasing severity |

## Model Performance

- Accuracy: ~85% (5-fold cross-validation)
- Precision: 0.83
- Recall: 0.85
- F1-score: 0.84

## Requirements

- Python 3.6+
- scikit-learn
- pandas
- numpy
- matplotlib

## Limitations

1. Based on limited dataset (303 samples)
2. Uses clinical data only (no imaging)
3. Predictions should be verified by doctors

## Citation
@misc{heart-disease,
author = {UCI Machine Learning Repository},
title = {Cleveland Heart Disease Data},
year = {1988},
howpublished = {https://archive.ics.uci.edu/ml/datasets/Heart+Disease}
}




**Note:** Always consult medical professionals for actual diagnoses.
