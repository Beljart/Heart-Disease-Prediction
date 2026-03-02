# Heart Disease Prediction App

A Machine Learning based web application that predicts the likelihood of heart disease using patient medical data.

## Project Overview

This project uses a trained Machine Learning model to predict whether a person is likely to have heart disease based on various health parameters.

The model is built using Python and deployed using Flask as a web application.

## Features

- Machine Learning model trained on heart disease dataset
- Web interface using Flask
- User-friendly input form
- Real-time prediction result
- Model accuracy: ~88%

## Input Parameters

The app uses the following medical attributes:

- Age
- Sex
- Chest Pain Type (cp)
- Resting Blood Pressure (trestbps)
- Cholesterol (chol)
- Fasting Blood Sugar (fbs)
- Rest ECG (restecg)
- Max Heart Rate (thalach)
- Exercise Induced Angina (exang)
- Oldpeak
- Slope
- Number of Major Vessels (ca)
- Thal

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Flask
- HTML

## Project Structure

Heart-Disease-Prediction/
│
├── app.py
├── train_model.py
├── model.pkl
├── heart.csv
│
└── templates/
    └── index.html

## How to Run the Project

1. Install required libraries:

pip install flask pandas numpy scikit-learn

2. Train the model:

python train_model.py

3. Run the Flask app:

python app.py

4. Open in browser:

http://127.0.0.1:5000

## Future Improvements

- Improve UI design
- Deploy online (Render / Railway / Heroku)
- Add data validation
- Add visualization dashboard

