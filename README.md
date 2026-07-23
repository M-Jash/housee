
🏡 House Price Predictor
An end-to-end Machine Learning web application that estimates residential property values based on key features (e.g., location, square footage, number of bedrooms/bathrooms, and property condition). Built with Python, Scikit-Learn, and Streamlit.

🔗 Live Web Application: housepricepredictor-09j8.streamlit.app

🌟 Key Features
Interactive UI: User-friendly web dashboard powered by Streamlit for instant predictions.

Real-Time Inference: Instantaneous price estimations based on trained machine learning regression models.

Feature Customization: Adjust property parameters such as area (sqft), location/neighborhood, bedrooms, bathrooms, and building age via simple sliders and dropdowns.

Data Preprocessing & Pipeline: Automated handling of missing values, feature scaling (StandardScaler), and categorical encoding (OneHotEncoder).
🛠️ Tech Stack
Frontend / Web UI: Streamlit

Data Processing: pandas, numpy

Machine Learning: scikit-learn (Linear Regression / Random Forest / XGBoost)

Model Serialization: joblib / pickle

Environment Management: pip / virtualenv
house-price-predictor/
│
├── dataset/
│   └── housing.csv             # Raw or processed housing dataset
│
├── models/
│   ├── model.pkl               # Saved trained Machine Learning model
│   └── scaler.pkl              # Scaler / Preprocessor object
│
├── .streamlit/
│   └── config.toml             # Streamlit UI theme configuration
│
├── app.py                      # Main Streamlit web application script
├── train_model.py              # Script to clean data, train model, and export artifacts
├── requirements.txt            # Python dependencies
├── .gitignore                  # Git ignore rules
└── README.md                   # Project documentation

📊 Model Training PipelineIf you want to re-train or fine-tune the machine learning model:Place your updated CSV file into the dataset/ directory.Run the training script:Bashpython train_model.py
The script will preprocess the dataset, train the regression model, print performance metrics ($R^2$ score, MAE, RMSE), and update the saved .pkl artifacts in the models/ directory.
