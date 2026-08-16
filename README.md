# 🏠 Real Estate Price Prediction

## 📌 Project Overview

This project presents an end-to-end Machine Learning application for predicting residential property prices based on property features such as total area, BHK, bathrooms, and location.

The project includes data cleaning and preprocessing using Jupyter Notebook, Machine Learning model training, model saving, Flask API development, and an interactive web interface for price prediction.

---

## 🖥️ Application Preview

![Real Estate Price Prediction](./screenshot.png)

The web application allows users to enter property details and get an estimated property price.

---

## 🎯 Objectives

- Predict residential property prices using Machine Learning.
- Clean and preprocess real estate data.
- Perform exploratory data analysis.
- Handle outliers and improve data quality.
- Perform feature engineering.
- Train and evaluate a Machine Learning model.
- Save the trained model for deployment.
- Build a Flask backend API.
- Connect the ML model with a web interface.
- Provide real-time property price predictions.

---

## 🔄 Project Workflow

```text
Raw Dataset
     ↓
Data Cleaning
     ↓
Exploratory Data Analysis
     ↓
Feature Engineering
     ↓
Outlier Removal
     ↓
Model Training
     ↓
Model Evaluation
     ↓
Save Trained Model
     ↓
Flask API
     ↓
Web Interface
     ↓
Price Prediction

## 📊 Input Features

The application uses the following features for prediction:

Feature	Description
Total Sqft	Total property area in square feet
BHK	Number of bedrooms
Bath	Number of bathrooms
Location	Location of the property
🧹 Data Cleaning & Preprocessing

Data cleaning and preprocessing were performed using Jupyter Notebook.

The preprocessing workflow includes:

Dataset exploration
Data cleaning
Handling data quality issues
Location data processing
Feature engineering
Outlier detection
Outlier removal
Preparing data for Machine Learning

The complete Machine Learning workflow is available in:

Real_Estate_price_Prediction.ipynb
## 🤖 Machine Learning

The cleaned and preprocessed dataset was used to train a Machine Learning model for property price prediction.

The trained model is saved using Pickle and is used by the Flask backend during prediction.

Model Files
Real_Estate_price_Prediction.pickle
columns.json

columns.json contains the feature/column information required by the prediction system.

## 🌐 Web Application

The project includes a web-based interface where users can enter:

🏠 Total property area
🛏 BHK
🛁 Number of bathrooms
📍 Location

After entering the required details, the user can click Estimate Price to get the predicted property price.

##🔌 Flask API

Flask is used as the backend framework to connect the Machine Learning model with the frontend.

📍 Get Location Names
GET /get_location_names

This API retrieves the available property locations dynamically.

💰 Predict Home Price
POST /predict_home_price

This API receives the property details and returns the estimated property price.

Example Input
total_sqft = 1000
bhk = 2
bath = 2
location = "Rajaji Nagar"
🛠 Tools Used
Python
Jupyter Notebook
Pandas
NumPy
Matplotlib
Scikit-learn
Flask
HTML5
CSS3
JavaScript
jQuery
JSON
Pickle
PyCharm
Git
GitHub
## 📓 Jupyter Notebook

The Machine Learning and data-cleaning process was performed in:

Real_Estate_price_Prediction.ipynb

The notebook contains the development process from data preparation to Machine Learning model creation.

📁 Important Files
File	Purpose
app.html	Frontend HTML structure
app.css	Website styling
app.js	Frontend JavaScript and API communication
server.py	Flask backend
main.py	Supporting Python code
util.py	Model loading and prediction utilities
columns.json	Model feature/column information
Real_Estate_price_Prediction.ipynb	Data cleaning and ML workflow
Real_Estate_price_Prediction.pickle	Trained Machine Learning model

📂 Project Structure
Real-Estate-Price-Prediction/
│
├── Client/
│   ├── app.html
│   ├── app.css
│   └── app.js
│
├── model/
│   ├── columns.json
│   ├── Real_Estate_price_Prediction.ipynb
│   └── Real_Estate_price_Prediction.pickle
│
├── server/
│   ├── Artifacts/
│   ├── main.py
│   ├── server.py
│   └── util.py
│
├── .gitignore
└── README.md

▶️ How to Run
1. Clone the Repository
git clone YOUR_GITHUB_REPOSITORY_URL
2. Open the Project

Open the project in PyCharm or VS Code.

3. Install Required Libraries
pip install flask pandas numpy matplotlib scikit-learn
4. Start the Flask Server

Open the terminal inside the server folder:

cd server

Run:

python server.py
5. Open the Application

The Flask application runs locally at:

http://127.0.0.1:5000

Make sure the Flask server is running while using the prediction application.

##💡 Key Features
🧹 Real-world data cleaning
📊 Exploratory Data Analysis
⚙️ Feature engineering
🚫 Outlier handling
🤖 Machine Learning prediction
💾 Model serialization
🌐 Flask REST API
📍 Dynamic location loading
🖥️ Interactive web interface
💰 Property price prediction
