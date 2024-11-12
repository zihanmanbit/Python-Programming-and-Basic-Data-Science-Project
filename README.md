# Python-Programming-and-Basic-Data-Science-Project
Digital Skills for Students Training Program<br>
Under “Enhancing Digital Government and Economy (EDGE) Project” of<br>
Bangladesh Computer Council of ICT Division<br>
Institute of Information and Communication Technology (IICT)<br>
Shahjalal University of Science and Technology, Sylhet 3114<br>

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Stroke Prediction Project</title>
</head>
<body>

# Stroke Prediction Project

This project builds a predictive model to assess the likelihood of stroke occurrence based on patient health and lifestyle data. By analyzing a range of attributes from age and BMI to medical history and smoking status, the model aims to identify factors that contribute most significantly to stroke risk. The insights gained from this project can assist in early intervention and targeted healthcare strategies.

## Dataset

The project uses the **Stroke Prediction Dataset** sourced from Kaggle. The dataset contains 5,110 records with the following columns:

- `gender`
- `age`
- `hypertension`
- `heart_disease`
- `ever_married`
- `work_type`
- `Residence_type`
- `avg_glucose_level`
- `bmi`
- `smoking_status`
- `stroke`

## Project Steps

### Data Preprocessing
- Handle missing values in the dataset.
- Convert categorical features into numerical values.

### Exploratory Data Analysis
- Conduct data visualization to understand the distribution of stroke-related attributes.

### Model Training
- Split the dataset into training and testing subsets.
- Train various machine learning models to identify the best-performing algorithm.

### Model Evaluation
- Evaluate model performance using appropriate metrics.
- Choose the model with the highest predictive accuracy for deployment.

### Predictive System
- Build a user-friendly predictive system that provides insights based on new input data.

## Requirements

To run this project, the following libraries are needed:
- `pandas`
- `numpy`
- `scikit-learn`
- `matplotlib`
- `seaborn`

You can install these libraries using:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn

