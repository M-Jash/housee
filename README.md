INTERNSHIP ID: CITS2924
NAME : MADAM JASHWANTH 
WEEKS : 8
PROJECT NAME :  House Price Predictor
# 🏠 House Price Predictor

A Machine Learning web application that predicts the estimated price of a house based on property features entered by the user. The application is built using **Python**, **Scikit-learn**, and **Streamlit**, providing an interactive interface for real-time house price prediction.

🌐 **Live Demo:** https://housepricepredictor-09j8.streamlit.app/

---

## 📌 Project Overview

House prices are influenced by several factors such as the size of the property, number of bedrooms, bathrooms, location, and other housing features. This project leverages a supervised machine learning regression model to estimate the selling price of a house from user-provided inputs.

The project demonstrates the complete machine learning workflow, including:

* Data preprocessing
* Feature engineering
* Model training
* Model evaluation
* Deployment as a web application using Streamlit

---

## 🚀 Features

* 🏡 Predict house prices instantly
* 📊 Interactive and user-friendly Streamlit interface
* ⚡ Real-time predictions
* 🤖 Machine Learning regression model
* 📱 Responsive web application
* ☁️ Deployed on Streamlit Cloud

---

## 🛠️ Tech Stack

### Programming Language

* Python

### Machine Learning

* Scikit-learn
* Pandas
* NumPy

### Visualization

* Matplotlib
* Seaborn

### Web Framework

* Streamlit

---

## 📂 Project Structure

```
House-Price-Predictor/
│
├── app.py                 # Streamlit application
├── model.pkl              # Trained ML model
├── dataset.csv            # Dataset
├── requirements.txt       # Required libraries
├── README.md
└── notebooks/
      └── model_training.ipynb
```

---

## ⚙️ How It Works

1. User enters property details.
2. Input data is preprocessed.
3. The trained regression model receives the processed input.
4. The model predicts the estimated house price.
5. The predicted price is displayed instantly on the web interface.

---

## 📊 Machine Learning Pipeline

```
Dataset
   │
   ▼
Data Cleaning
   │
   ▼
Feature Engineering
   │
   ▼
Train/Test Split
   │
   ▼
Model Training
   │
   ▼
Model Evaluation
   │
   ▼
Model Serialization
   │
   ▼
Streamlit Deployment
```

---

## 📈 Model Evaluation

The model was evaluated using standard regression metrics, including:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score

These metrics help assess how accurately the model predicts house prices.

---

## 💻 Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/house-price-predictor.git
```

Navigate into the project directory:

```bash
cd house-price-predictor
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
streamlit run app.py
```

---

## 📸 Application Preview

After launching the application:

* Enter house details.
* Click the **Predict** button.
* View the estimated house price instantly.

---

## 🎯 Learning Outcomes

This project demonstrates practical knowledge of:

* Machine Learning Regression
* Data Preprocessing
* Feature Engineering
* Model Training
* Model Evaluation
* Streamlit Application Development
* Machine Learning Model Deployment
* Python for Data Science

---

## 🔮 Future Improvements

* Integrate advanced regression models (XGBoost, CatBoost)
* Add interactive data visualizations
* Support multiple datasets
* Improve prediction accuracy through hyperparameter tuning
* Deploy using Docker and cloud services
* Add model explainability using SHAP values

---

## 👨‍💻 Author

**Jashwanth M**

If you found this project useful, feel free to ⭐ the repository and share your feedback.

---

## 📄 License

This project is intended for educational and portfolio purposes.
