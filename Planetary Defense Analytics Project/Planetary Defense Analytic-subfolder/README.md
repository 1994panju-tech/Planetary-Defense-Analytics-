# ☄️ Planetary Defense & Asteroid Intelligence System

## 📌 Project Overview

The Planetary Defense & Asteroid Intelligence System is a Machine Learning project developed to analyze asteroid data.

The main objective of this project is to identify potentially hazardous asteroids, estimate asteroid diameter, and group asteroids based on their orbital characteristics.

This project uses Python, Machine Learning, Explainable AI (SHAP), MLflow, and Streamlit.

The application currently runs locally on a computer and has not yet been deployed online.

## 🎯 Project Objectives

- Predict whether an asteroid is potentially hazardous.
- Estimate asteroid diameter in kilometers.
- Group asteroids based on their orbital characteristics.
- Explain model predictions using SHAP.
- Track machine learning experiments using MLflow.
- Display results through a Streamlit application.

## 📂 Project Use Cases

### Case 1: PHA Risk Assessment

This is a classification problem.

The model predicts whether an asteroid is potentially hazardous (PHA).

- **Input:** Asteroid orbital and physical features.
- **Output:** Hazardous or Non-Hazardous classification.
- **Evaluation Metrics:** Accuracy, Precision, Recall, F1-score, and ROC-AUC.
- **Explainable AI:** SHAP helps explain which features influence the predictions.

### Case 2: Asteroid Diameter Estimation

This is a regression problem.

The model predicts the diameter of an asteroid in kilometers.

- **Input:** Asteroid features.
- **Output:** Predicted asteroid diameter in kilometers.
- **Evaluation Metrics:** R² Score, RMSE, and MAE.
- **Explainable AI:** SHAP helps explain the model predictions.

### Case 3: Orbital Population Mapping

This is an unsupervised learning problem.

The objective is to group asteroids based on their orbital characteristics.

- **Algorithms:** K-Means and DBSCAN.
- **Input Features:** Orbital parameters such as semi-major axis, eccentricity, inclination, and other orbital features.
- **Output:** Asteroid clusters.
- **Evaluation:** Silhouette Score and other suitable clustering measures.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Matplotlib
- SHAP
- MLflow
- Streamlit
- Joblib
- Jupyter Notebook
- Visual Studio Code

## 📁 Project Structure

```text
Planetary Defense Analytics Project/
│
├── app01.py
├── README.md
├── requirements.txt
│
├── processed_data/
├── processed_regression/
├── saved_models/
├── results/
│
└── Jupyter Notebooks/
    ├── 01. Data Cleaning
    ├── 02. Data Preprocessing
    ├── 03. Classification
    ├── 04. Regression Preprocessing
    ├── 05. Regression
    ├── 06. Clustering
    ├── 07. Model Saving & Experiment Tracking
    └── 08. Explainable AI (SHAP)
```

## ⚙️ Installation and Setup

### Step 1: Install Python

Install Python on your computer and make sure it is available in the terminal.

### Step 2: Open the Project

Open the project folder in Visual Studio Code.

### Step 3: Install Required Libraries

Open the VS Code terminal and run:

```bash
python -m pip install -r requirements.txt
```

### Step 4: Run the Streamlit Application

Run the following command in the terminal:

```bash
streamlit run app01.py
```

### Step 5: Open the Application

After running the command, Streamlit will display a local URL in the terminal.

Open the URL in your browser. The default address is usually:

`http://localhost:8501`

The application can be accessed on your local computer while the Streamlit server is running.

## 📊 MLflow Experiment Tracking

MLflow is used to track machine learning experiments for Case 1 and Case 2.

It helps record model parameters, evaluation metrics, and trained model artifacts.

The classification metrics include Accuracy, Precision, Recall, F1-score, and ROC-AUC.

The regression metrics include R² Score, RMSE, and MAE.

To start the MLflow interface, open a separate VS Code terminal and run:

```bash
python -m mlflow ui
```

Open the following address in your browser:

`http://localhost:5000`

The MLflow interface allows you to view experiment runs and compare logged metrics.

## 🧠 Explainable AI Using SHAP

SHAP is used to explain machine learning predictions.

It helps identify important features and understand how they influence the model's predictions.

SHAP summary plots and individual explanations can help make model predictions easier to understand.

## 🚀 Expected Outcomes

- PHA risk classification.
- Asteroid diameter estimation.
- Asteroid orbital clustering.
- SHAP-based model explanations.
- MLflow experiment tracking.
- Interactive visualization through Streamlit.

## ⚠️ Disclaimer

This project is developed for educational and analytical purposes. The predictions should not be treated as official asteroid threat assessments or as a replacement for professional planetary defense analysis.

## 👩‍💻 Author

**Project Name:** Planetary Defense & Asteroid Intelligence System

**Domain:** Data Science and Machine Learning

**Application:** Streamlit

**Deployment Status:**  deployed online.


