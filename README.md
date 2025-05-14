# Liver Disease Prediction Web App

This is a **Streamlit-based web application** designed to predict liver disease based on various clinical parameters. It includes user authentication (sign-up and login), intuitive UI, and a pre-trained machine learning model for accurate predictions.

## 🚀 Features

- User Authentication (Sign Up & Login)
- Input form for liver function test parameters
- Predicts if a person is likely to have liver disease
- Displays prediction results with confidence
- Clean and user-friendly UI with `streamlit_option_menu`

## 🧪 Parameters Used

The app uses the following inputs for prediction:

- Age
- Total Bilirubin
- Direct Bilirubin
- Alkaline Phosphatase
- Alanine Aminotransferase (ALT)
- Aspartate Aminotransferase (AST)
- Total Proteins
- Albumin
- Albumin/Globulin Ratio

These are based on standard liver function test (LFT) results.

## 📈 Prediction Model

A pre-trained machine learning model (e.g., Random Forest, SVM, or Logistic Regression) is used to analyze the input data and return a prediction on whether the individual is likely to have liver disease.

> **Note**: The model must be trained separately and saved as a `.pkl` file. The current implementation expects the model to be named `liver_model.pkl`.

## 📦 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/liver-disease-prediction.git
   cd liver-disease-prediction
