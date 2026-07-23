
🏡 House Price PredictorAn end-to-end Machine Learning web application that estimates residential property values based on key features (e.g., location, square footage, number of bedrooms/bathrooms, and property condition). Built with Python, Scikit-Learn, and Streamlit.🔗 Live Web Application: housepricepredictor-09j8.streamlit.app🌟 Key FeaturesInteractive UI: User-friendly web dashboard powered by Streamlit for instant predictions.Real-Time Inference: Instantaneous price estimations based on trained machine learning regression models.Feature Customization: Adjust property parameters such as area (sqft), location/neighborhood, bedrooms, bathrooms, and building age via simple sliders and dropdowns.Data Preprocessing & Pipeline: Automated handling of missing values, feature scaling (StandardScaler), and categorical encoding (OneHotEncoder).🛠️ Tech StackFrontend / Web UI: StreamlitData Processing: pandas, numpyMachine Learning: scikit-learn (Linear Regression / Random Forest / XGBoost)Model Serialization: joblib / pickleEnvironment Management: pip / virtualenv📂 Project StructurePlaintexthouse-price-predictor/
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
🚀 Getting StartedFollow these steps to set up and run the project locally on your machine.PrerequisitesMake sure you have Python 3.9+ installed.1. Clone the RepositoryBashgit clone https://github.com/your-username/house-price-predictor.git
cd house-price-predictor
2. Create a Virtual EnvironmentBash# On macOS / Linux
python3 -m venv venv
source venv/bin/activate

# On Windows
python -m venv venv
venv\Scripts\activate
3. Install DependenciesBashpip install -r requirements.txt
4. Run the Streamlit AppBashstreamlit run app.py
The application will open automatically in your browser at http://localhost:8501.📊 Model Training PipelineIf you want to re-train or fine-tune the machine learning model:Place your updated CSV file into the dataset/ directory.Run the training script:Bashpython train_model.py
The script will preprocess the dataset, train the regression model, print performance metrics ($R^2$ score, MAE, RMSE), and update the saved .pkl artifacts in the models/ directory.
