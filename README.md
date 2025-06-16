## CORBEAT: A System for predicting Heart Disease ##

## Overview
CorBeat is a web-based heart disease risk assessment tool that analyzes user health data and predicts the likelihood of heart disease using a machine learning model. 
The project integrates Flask for backend processing and Firebase for authentication and data storage.


## Features
- **Risk Assessment Form:** Collects user basic data and calculates risk score.
- **Machine Learning Prediction:** Uses a trained model to predict heart disease risk using user provided medical data.
- **View List of Heart Specialist:** Display the list of heart specialists.
- **Flask Backend:** Handles form submissions and processes predictions.
- **Firebase Integration:** User authentication and real-time database storage.
- **Admin Dashboard:** Manage details of healthcare professionals and display the number of predictions,total number of doctors,users etc


## Installation

### Prerequisites
Ensure you have Python installed

Install dependencies:
pip install flask numpy pandas scikit-learn

## Usage
1. Start the Flask application:
   ```sh
   python app.py
   ```
2. Open your browser and navigate to:
   ```
   http://127.0.0.1:5000/
   ```
3. Register/Login to access the risk assessment tools.

## Project Structure
```
corbeat/
│── static/                 # CSS, JS, and images
│── templates/              # HTML templates
│── app.py                  # Main Flask application
|__ Dataset.csv             # Heart disease dataset
|__ Model.pkl               # ML trained model
|__ database.db             # store the number of prediction made using sqlite3
│── README.md               # Project documentation
```
![Alt text](static/images/project-1.png)
![Alt text](static/images/home-ss.png)

