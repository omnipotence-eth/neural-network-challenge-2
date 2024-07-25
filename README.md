# Employee Attrition and Department Prediction

This project uses a deep learning model to predict employee attrition and department based on various features.

## Dataset

The dataset contains employee information including:
- Age
- Business Travel
- Education
- Job Satisfaction
- Work Life Balance
- Years at Company
- and more

## Model

A multi-output neural network is used with:
- Shared layers for feature extraction
- Separate branches for Attrition and Department prediction
- Softmax activation for output layers

## Usage

1. Load and preprocess the data
2. Split into training and testing sets
3. Scale features using StandardScaler
4. Create and compile the neural network model
5. Train the model
6. Evaluate performance on test data

## Results

The model achieves:
- ~53% accuracy for Department prediction
- ~83% accuracy for Attrition prediction
- 
## Requirements

- pandas
- numpy
- sklearn
- tensorflow
