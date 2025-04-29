# logistcrt2
# Breast Cancer Classification with Logistic Regression

A comprehensive implementation of logistic regression for binary classification using Scikit-learn, featuring threshold tuning and performance visualization.

## Features

- **Binary Classification**: Predicts malignant/benign tumors using 30 biomedical features
- **Data Preprocessing**: Automatic feature standardization with `StandardScaler`
- **Model Evaluation**: Includes precision, recall, F1-score, and ROC-AUC metrics
- **Threshold Tuning**: Visualizes precision-recall tradeoffs and implements custom thresholding
- **Sigmoid Visualization**: Demonstrates probability conversion through logistic function

## Requirements


## Implementation Highlights

1. **Data Preparation**
   - Uses Scikit-learn's breast cancer dataset
   - Automatic train-test split (80-20 ratio)
   - Feature standardization preserving original distributions

2. **Model Configuration**
   - L2 regularization (Ridge penalty)
   - `liblinear` solver optimized for small datasets
   - Random state reproducibility

3. **Advanced Evaluation**
   - Interactive precision-recall curve analysis
   - Custom threshold selection for recall optimization
   - ROC curve with AUC scoring

4. **Visualizations**
   - Sigmoid activation function plot
   - ROC curve comparison
   - Confusion matrix heatmap (via Seaborn in code comments)

