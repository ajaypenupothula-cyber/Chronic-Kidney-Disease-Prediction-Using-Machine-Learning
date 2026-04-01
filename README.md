# Chronic Kidney Disease (CKD) Prediction Web Application

This project implements a machine learning model to predict Chronic Kidney Disease (CKD) based on various medical parameters.

## Features
- Random Forest Classifier for CKD prediction
- Data preprocessing and scaling
- Model evaluation with classification report
- Visual analysis with confusion matrix and feature importance plots
- Sample data generation for demonstration

## Requirements
- Python 3.7+
- Required packages listed in `requirements.txt`

## Installation
```bash
pip install -r requirements.txt
```

## Usage
Run the Flask application:
```bash
python app.py
```

The server will start at `http://localhost:5002`

## Model Features
The prediction model uses the following medical parameters:
- Age
- Blood Pressure
- Specific Gravity
- Albumin
- Blood Glucose
- Blood Urea
- Serum Creatinine
- Sodium
- Potassium
- Hemoglobin

## Security Features
- Password hashing
- File upload restrictions
- User session management
- Maximum file size limits
- Secure filename handling
