# 🏠 REAL ESTATE PRICE PREDICTION

## 📌 PROJECT OVERVIEW

This project presents an end-to-end Machine Learning application for predicting residential property prices based on property features such as total area, BHK, bathrooms, and location.

The project includes data cleaning and preprocessing using Jupyter Notebook, Machine Learning model training, model saving, Flask API development, and an interactive web interface for property price prediction.

---

## 🖥️ APPLICATION PREVIEW

![Real Estate Price Prediction](./screenshot.png)

The web application allows users to enter property details and get an estimated property price.

---

## 🎯 OBJECTIVES

- Predict residential property prices using Machine Learning.
- Clean and preprocess real estate data.
- Perform Exploratory Data Analysis.
- Handle outliers and improve data quality.
- Perform feature engineering.
- Train and evaluate a Machine Learning model.
- Save the trained model for deployment.
- Build a Flask backend API.
- Connect the Machine Learning model with a web interface.
- Provide property price predictions through the web application.

---

## 🔄 PROJECT WORKFLOW

```text
Raw Real Estate Dataset
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
   Save ML Model
          ↓
      Flask API
          ↓
   Web Application
          ↓
 Property Price Prediction
```

---

## 📊 INPUT FEATURES

The application uses the following features for prediction:

| FEATURE | DESCRIPTION |
|---|---|
| Total Sqft | Total property area in square feet |
| BHK | Number of bedrooms |
| Bath | Number of bathrooms |
| Location | Location of the property |

---

## 🧹 DATA CLEANING & PREPROCESSING

Data cleaning and preprocessing were performed using **Jupyter Notebook**.

The preprocessing workflow includes:

- Dataset exploration
- Data cleaning
- Handling data quality issues
- Location data processing
- Feature engineering
- Outlier detection
- Outlier removal
- Preparing data for Machine Learning

The complete Machine Learning workflow is available in:

```text
Real_Estate_price_Prediction.ipynb
```

---

## 🤖 MACHINE LEARNING

The cleaned and preprocessed dataset was used to train a Machine Learning model for property price prediction.

The trained model is saved using **Pickle** and is used by the Flask backend during prediction.

### 📦 MODEL FILES

```text
Real_Estate_price_Prediction.pickle
columns.json
```

`columns.json` contains the feature and column information required by the prediction system.

---

## 🌐 WEB APPLICATION

The project includes a web-based interface where users can enter:

- 🏠 Total property area
- 🛏️ BHK
- 🛁 Number of bathrooms
- 📍 Location

After entering the required details, the user can click **Estimate Price** to get the predicted property price.

---

## 🔌 FLASK API

Flask is used as the backend framework to connect the Machine Learning model with the frontend.

### 📍 GET LOCATION NAMES

**METHOD: GET**

```text
/get_location_names
```

This API retrieves the available property locations dynamically.

### 💰 PREDICT HOME PRICE

**METHOD: POST**

```text
/predict_home_price
```

This API receives the property details and returns the estimated property price.

### EXAMPLE INPUT

```text
total_sqft = 1000
bhk = 2
bath = 2
location = "Rajaji Nagar"
```

---

## 🛠️ TOOLS USED

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Flask
- HTML5
- CSS3
- JavaScript
- JSON
- Pickle
- PyCharm
- GitHub

---

## 📓 JUPYTER NOTEBOOK

The Machine Learning and data-cleaning process was performed in:

```text
Real_Estate_price_Prediction.ipynb
```

The notebook contains the development process from data preparation and cleaning to Machine Learning model creation.

---

## 📁 IMPORTANT PROJECT FILES

| FILE | PURPOSE |
|---|---|
| `app.html` | Frontend HTML structure |
| `app.css` | Website styling |
| `app.js` | Frontend JavaScript and API communication |
| `server.py` | Flask backend |
| `main.py` | Supporting Python code |
| `util.py` | Model loading and prediction utilities |
| `columns.json` | Model feature and column information |
| `Real_Estate_price_Prediction.ipynb` | Data cleaning and Machine Learning workflow |
| `Real_Estate_price_Prediction.pickle` | Trained Machine Learning model |

---

## 📂 PROJECT STRUCTURE

```text
ML Project/
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

└── README.md
```

---

## ▶️ HOW TO RUN

### 1️⃣ CLONE THE REPOSITORY

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### 2️⃣ OPEN THE PROJECT

Open the project in **PyCharm** or **VS Code**.

### 3️⃣ INSTALL REQUIRED LIBRARIES

```bash
pip install flask pandas numpy matplotlib scikit-learn
```

### 4️⃣ START THE FLASK SERVER

Open the terminal inside the `server` folder:

```bash
cd server
```

Run the Flask server:

```bash
python server.py
```

### 5️⃣ OPEN THE APPLICATION

The Flask application runs locally at:

```text
http://127.0.0.1:5000
```

Make sure the Flask server is running while using the prediction application.

---

## 💡 KEY FEATURES

- 🧹 Real-world data cleaning
- 📊 Exploratory Data Analysis
- ⚙️ Feature engineering
- 🚫 Outlier handling
- 🤖 Machine Learning prediction
- 💾 Model serialization
- 🌐 Flask REST API
- 📍 Dynamic location loading
- 🖥️ Interactive web interface
- 💰 Property price prediction

---

## 📈 PREDICTION PROCESS

```text
USER ENTERS PROPERTY DETAILS
              ↓
       FRONTEND REQUEST
              ↓
          FLASK API
              ↓
      SAVED ML MODEL
              ↓
     PREDICTION GENERATED
              ↓
     ESTIMATED PRICE
       DISPLAYED ON PAGE
```

---


## 🎓 LEARNING OUTCOMES

Through this project, I gained practical experience in building an end-to-end Machine Learning application, from preparing and cleaning real-world data to integrating a trained Machine Learning model with a Flask-based web application.

---


## 👩‍💻 AUTHOR

**Shruti Hule**

BE Computer Engineering Student

**Aspiring Data Analyst | Machine Learning | Python | SQL | Power BI**

---


