🏠 #Home Price Prediction

A Machine Learning web application that predicts the estimated price of a residential property based on its area, number of bedrooms, bathrooms, and location.

The project covers the complete Machine Learning workflow — from data cleaning and preprocessing to model training and deployment through a Flask-based web application.

📌 Project Overview

Real estate prices depend on several factors such as property size, number of bedrooms, bathrooms, and location.

This project uses real estate data to build a Machine Learning model capable of estimating property prices based on user-provided property details.

The trained model is integrated with a Flask backend and a web-based frontend, allowing users to enter property information and receive an estimated price.

✨ Key Features
📊 Data cleaning and preprocessing
🔍 Exploratory Data Analysis
🧹 Outlier detection and removal
⚙️ Feature engineering
🤖 Machine Learning model training
📈 Model evaluation
💾 Saved trained ML model
🌐 Flask REST API
📍 Dynamic location selection
🖥️ Interactive web interface
💰 Real-time property price prediction
🛠️ Technologies Used
Programming Language
Python
Data Analysis & Machine Learning
Pandas
NumPy
Matplotlib
Scikit-learn
Jupyter Notebook
Backend
Flask
Python
Frontend
HTML5
CSS3
JavaScript
jQuery
Model & Data Storage
Pickle
JSON
Development Tools
PyCharm
Jupyter Notebook
Git
GitHub
📂 Project Structure
real-estate-price-prediction/
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
🔄 Project Workflow
                 Raw Real Estate Data
                         │
                         ▼
                 Data Cleaning
                         │
                         ▼
              Exploratory Data Analysis
                         │
                         ▼
                 Feature Engineering
                         │
                         ▼
                  Outlier Removal
                         │
                         ▼
                 Model Training
                         │
                         ▼
                 Model Evaluation
                         │
                         ▼
                  Save ML Model
                         │
                         ▼
                    Flask API
                         │
                         ▼
                  Web Application
                         │
                         ▼
              Predicted Property Price
🧹 Data Cleaning & Preprocessing

Data cleaning and preprocessing were performed using Jupyter Notebook.

The notebook contains the data preparation and Machine Learning workflow required to prepare the real estate dataset for prediction.

The main preprocessing activities include:

Exploring the dataset
Handling data quality issues
Cleaning property information
Processing location data
Feature engineering
Identifying outliers
Removing unsuitable observations
Preparing features for Machine Learning

The complete notebook is available at:

model/Real_Estate_price_Prediction.ipynb
📊 Machine Learning

The cleaned dataset is used to train a Machine Learning model for property price prediction.

The application uses the following inputs:

Input	Description
Total Sqft	Total property area in square feet
BHK	Number of bedrooms
Bath	Number of bathrooms
Location	Location of the property

The trained model is saved as:

Real_Estate_price_Prediction.pickle

The feature/column information used by the application is stored in:

columns.json
🌐 Web Application

The frontend provides an interface where users can enter property details.

User Inputs

1. Area

The total property area in square feet.

2. BHK

Number of bedrooms.

3. Bathrooms

Number of bathrooms.

4. Location

Property location selected from the available locations.

After entering the required information, the user can click:

Estimate Price

The request is sent to the Flask backend, where the trained Machine Learning model generates the estimated property price.

🔌 Flask API

The Flask application acts as the bridge between the frontend and the Machine Learning model.

Get Location Names
GET /get_location_names

This endpoint provides the locations available for prediction.

Predict Property Price
POST /predict_home_price

This endpoint accepts property information and returns the estimated price.

Example Input
total_sqft = 1000
bhk = 2
bath = 2
location = "Rajaji Nagar"

The backend processes these values and passes them to the trained Machine Learning model.

▶️ How to Run the Project Locally
1. Clone the Repository
git clone YOUR_GITHUB_REPOSITORY_URL

Navigate into the project:

cd real-estate-price-prediction
2. Install Required Libraries

Install the required Python packages:

pip install flask pandas numpy matplotlib scikit-learn

If you want to work with the notebook:

pip install jupyter
3. Start the Flask Server

Open the terminal in the server directory:

cd server

Run:

python server.py

If everything is configured correctly, Flask will start the local server:

http://127.0.0.1:5000
4. Open the Application

Open the application using your configured frontend/Flask setup.

Make sure the Flask server is running before using the prediction feature because the frontend communicates with the backend API.

📓 Jupyter Notebook

The Machine Learning development process is documented in:

model/Real_Estate_price_Prediction.ipynb

The notebook contains the data preparation and model development workflow.

The notebook is an important part of this project because it shows the data cleaning and Machine Learning process before the model is connected to the Flask application.

📁 Important Project Files
File	Purpose
app.html	Web application structure
app.css	Website styling and UI
app.js	Frontend interaction and API requests
server.py	Flask application/API
util.py	Model loading and prediction-related utility functions
main.py	Supporting Python application code
columns.json	Feature/column information
Real_Estate_price_Prediction.ipynb	Data cleaning and ML workflow
Real_Estate_price_Prediction.pickle	Saved trained ML model
🎯 Project Objective

The objective of this project is to build an end-to-end Machine Learning application that can estimate residential property prices using property characteristics.

The project demonstrates how a Machine Learning model can be transformed into a usable web application.

From Data to Application
Data
 ↓
Cleaning
 ↓
Analysis
 ↓
Feature Engineering
 ↓
Machine Learning
 ↓
Model Saving
 ↓
Flask API
 ↓
Frontend
 ↓
Price Prediction
💡 Learning Outcomes

Through this project, I gained practical experience in:

Python programming
Data cleaning
Data preprocessing
Exploratory Data Analysis
Feature engineering
Outlier handling
Machine Learning
Model evaluation
Model serialization
Flask
REST API development
HTML
CSS
JavaScript
Frontend-backend integration
Git and GitHub
🚀 Future Improvements

The project can be further improved by adding:

📊 Model performance dashboard
📈 Prediction confidence information
🏘️ More property features
🗺️ Map-based location selection
📱 Fully responsive mobile interface
🔐 User authentication
🗄️ Database integration
☁️ Cloud deployment
🔄 Multiple model comparison
📊 Interactive data visualizations
📸 Application Preview

Add screenshots of your application here.

Create a folder:

screenshots/

Then add your screenshots and reference them in the README.

Example:

![Home Page](screenshots/home-page.png)
