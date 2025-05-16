# 🍷 Wine Quality Prediction using Machine Learning

This project predicts the quality of wine based on various physicochemical properties using a **Random Forest**. It includes data analysis, model training, evaluation, and a simple user interface using Flask.

---

## 📂 Project Structure
WINE/
  Flask_app/
  ├── templates/
    └──home.html # Home page
    └── index.html # Frontend for user input
    └── pred.html # Predict result of given user inputs
  ├── app.py # Flask app for model deployment
  ├── wineQuality_new.pkl # Trained Random Forest model

  Training/
  └── WineQuality.ipynb # Data analysis and model training(full code)
  └── Wineflask.ipynb # For Flask purpose only
  └── winequality-red.csv # Dataset used
  ├── requirements.txt # Python dependencies
  └── README.md # Project documentation



### 🍷 Wine Quality Prediction Using Machine Learning

This project focuses on predicting the **quality of wine** based on its physicochemical features using a **Random Forest Regressor**, a robust and widely used machine learning algorithm.

Wine quality, as rated by human tasters, is influenced by various factors such as acidity, sugar content, alcohol percentage, and sulfur dioxide levels. With the help of machine learning, we aim to automate the prediction of wine quality scores using these measurable properties.

The application is deployed using **Flask**, providing a simple and interactive web interface where users can input wine characteristics and receive a predicted quality score.
