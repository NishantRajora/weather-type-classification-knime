# Weather Type Classification using KNIME

## Overview

This project focuses on weather type classification and temperature prediction using the KNIME Analytics Platform.  

The objective is to design a complete machine learning workflow — from data preprocessing and outlier handling to model training and evaluation — using a synthetic weather dataset.

The project demonstrates practical knowledge of:

- Data preprocessing in KNIME  
- Handling categorical and numerical features  
- Classification model comparison  
- Basic regression modeling  
- Workflow-based machine learning design  

---

## Project Objectives

- Classify weather conditions into predefined categories  
- Predict temperature using supervised learning techniques  
- Compare multiple classification algorithms  
- Handle intentional outliers present in the dataset  
- Build a reproducible KNIME workflow  

---

## Dataset Details

Source: Kaggle  
https://www.kaggle.com/datasets/nikhil7280/weather-type-classification  

The dataset contains synthetically generated weather records for educational purposes.

### Features

- Temperature (°C)  
- Humidity (%)  
- Wind Speed (km/h)  
- Precipitation (%)  
- Atmospheric Pressure (hPa)  
- UV Index  
- Visibility (km)  
- Cloud Cover (categorical)  
- Season (categorical)  
- Location (categorical)  

### Target Variables

- Weather Type (Classification Task)  
  - Rainy  
  - Sunny  
  - Cloudy  
  - Snowy  

- Temperature (Regression Task)

Note: The dataset includes intentional outliers to simulate real-world noise and improve preprocessing skills.

---

## Tools and Technologies

- KNIME Analytics Platform  
- Machine Learning Nodes  
- Data Preprocessing Nodes  
- Statistical & Visualization Nodes  
- Model Evaluation Nodes  

---

## Workflow Architecture

The KNIME workflow follows a structured pipeline:

1. Data Loading  
   - CSV Reader Node  

2. Data Cleaning  
   - Missing value handling  
   - Outlier detection and filtering  
   - Range validation  

3. Feature Engineering  
   - Encoding categorical variables  
   - Normalization or scaling (if required)  
   - Column filtering  

4. Data Splitting  
   - Train-Test Split (typically 70:30 or 80:20)  

5. Model Training  
   - Multiple classification algorithms  
   - Optional regression workflow for temperature prediction  

6. Model Evaluation  
   - Accuracy calculation  
   - Confusion matrix  
   - Precision, recall, and F1-score  
   - Prediction comparison view  

---

## Algorithms Implemented

### Classification Models

- Decision Tree  
- Random Forest  
- Naive Bayes  
- Logistic Regression  
- K-Nearest Neighbors (KNN)  

### Regression (Temperature Prediction)

- Linear Regression (if implemented)  
- Tree-based regression models (optional)  

Model selection was performed by comparing performance metrics.

---

## Model Evaluation Metrics

Classification models were evaluated using:

- Accuracy  
- Confusion Matrix  
- Precision  
- Recall  
- F1-Score  

Regression performance was evaluated using:

- Mean Absolute Error (MAE)  
- Mean Squared Error (MSE)  
- R² Score  

---

## Key Observations

- Tree-based models (Decision Tree, Random Forest) generally performed better on structured weather data.  
- Proper encoding of categorical features significantly improved classification performance.  
- Outlier handling reduced noise and improved model stability.  
- Ensemble models demonstrated better generalization compared to single-model classifiers.  

---

## Learning Outcomes

- Practical implementation of end-to-end ML pipeline in KNIME  
- Understanding of classification vs regression workflows  
- Experience with preprocessing and outlier detection  
- Comparative evaluation of multiple algorithms  
- Workflow-based visual machine learning development  

---

## Future Improvements

- Hyperparameter tuning using KNIME parameter optimization loops  
- Cross-validation workflow implementation  
- Feature importance analysis  
- Deployment as an interactive KNIME WebPortal application  
- Exporting model for integration into Python-based systems  

---

## Repository Structure

```
Weather-Type-Classification-KNIME/
│
├── data/
├── workflow.knwf
├── screenshots/
└── README.md
```

---

## Author

Nishant Rajora  
Data Science Undergraduate  
Focused on practical machine learning implementation and workflow-based analytics
