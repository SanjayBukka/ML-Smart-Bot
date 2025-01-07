# ML Smart Bot

This repository contains a Streamlit-based web application for building, training, and evaluating machine learning models. The app supports both regression and classification tasks and provides tools for exploratory data analysis (EDA).

## Features

- **Dataset Upload:** Upload your dataset in CSV format for analysis and modeling.
- **Exploratory Data Analysis (EDA):**
  - Display dataset information, column details, and statistical summaries.
  - Visualize data with various plots, including correlation heatmaps and feature importance charts.
- **Model Training:**
  - Choose from various regression and classification algorithms.
  - Customize hyperparameters for models.
- **Model Evaluation:**
  - View key performance metrics for regression (e.g., RMSE, MAE) and classification (e.g., accuracy, precision, recall).
  - Visualize model predictions and evaluation results.
- **User-Friendly Interface:** Built using Streamlit for an interactive and seamless user experience.

## Installation

Follow these steps to run the application locally:

### Prerequisites

Ensure you have Python 3.8 or higher installed. Install the required libraries using pip.

## How to Use

1. **Upload Dataset:**
   - Click the "Browse files" button to upload a CSV file.
2. **Explore Data:**
   - Use the EDA section to view dataset statistics and visualizations.
3. **Train Model:**
   - Choose a task type (regression or classification).
   - Select an algorithm and adjust hyperparameters as needed.
4. **Evaluate Model:**
   - View performance metrics and visualizations of the model's predictions.

## Supported Algorithms

### Regression:
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting Regressor

### Classification:
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Gradient Boosting Classifier

## File Structure

```
.
├── app.py                 # Main Streamlit application
├── requirements.txt       # Python dependencies
├── README.md              # Project documentation
└── data/                  # Sample datasets (optional)
```

## Dependencies

The required libraries are listed in `requirements.txt`. Key dependencies include:

- `streamlit`
- `pandas`
- `numpy`
- `scikit-learn`
- `matplotlib`
- `seaborn`
