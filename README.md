# 🩺 Liver Cirrhosis Stage Detection using Machine Learning

##  Project Overview

Liver cirrhosis is a serious medical condition caused by long-term liver damage. Early detection of the stage of liver cirrhosis can help doctors make better treatment decisions.

This project builds a **Machine Learning model** that predicts the **stage of liver cirrhosis** using patient medical data such as bilirubin level, cholesterol, platelets, liver enzymes, and other clinical measurements.

The dataset used in this project originates from a **Primary Biliary Cirrhosis (PBC) study conducted by the Mayo Clinic between 1974 and 1984.**

---

##  Objective

The main goal of this project is to develop a **classification model** that predicts the **stage of liver cirrhosis (Stage 1, 2, or 3)** based on patient health indicators.

This project demonstrates:

* Medical data analysis
* Data preprocessing
* Feature encoding
* Machine learning classification
* Model evaluation

---

##  Dataset Information

The dataset contains patient health information related to liver disease.

### Important Features

| Column        | Description                                         |
| ------------- | --------------------------------------------------- |
| N_Days        | Days between registration and outcome               |
| Status        | Patient status (C, CL, D)                           |
| Drug          | Drug type (D-penicillamine or placebo)              |
| Age           | Age of patient in days                              |
| Sex           | Gender (Male/Female)                                |
| Ascites       | Presence of ascites                                 |
| Hepatomegaly  | Liver enlargement                                   |
| Spiders       | Presence of spider veins                            |
| Edema         | Edema condition                                     |
| Bilirubin     | Serum bilirubin level                               |
| Cholesterol   | Serum cholesterol                                   |
| Albumin       | Albumin level                                       |
| Copper        | Urine copper level                                  |
| Alk_Phos      | Alkaline phosphatase level                          |
| SGOT          | Liver enzyme level                                  |
| Tryglicerides | Triglyceride level                                  |
| Platelets     | Platelet count                                      |
| Prothrombin   | Blood clotting time                                 |
| Stage         | Histologic stage of liver disease (Target Variable) |

---

##  Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab

---

##  Machine Learning Workflow

### 1. Data Collection

Medical dataset from a liver cirrhosis study.

### 2. Data Preprocessing

* Handling missing values
* Encoding categorical variables
* Cleaning dataset

### 3. Feature Engineering

Converted categorical features using **One-Hot Encoding**.

### 4. Model Training

Used **Random Forest Classifier** to train the model.

### 5. Model Evaluation

Model performance evaluated using:

* Accuracy Score
* Confusion Matrix

---

##  Model Performance

The model achieved **good classification accuracy**, showing that machine learning can assist in identifying the stage of liver disease using patient medical data.

---

##  Project Structure

```
Liver-Cirrhosis-Stage-Prediction
│
├── liver_cirrhosis_prediction.ipynb
├── cirrhosis.csv
├── liver_cirrhosis_model.pkl
└── README.md
```

---

##  How to Run the Project

### Step 1

Clone the repository

```
git clone https://github.com/yourusername/Liver-Cirrhosis-Stage-Prediction.git
```

### Step 2

Open the notebook in **Google Colab** or **Jupyter Notebook**

### Step 3

Install required libraries

```
pip install pandas numpy scikit-learn matplotlib seaborn
```

### Step 4

Run all cells in the notebook to train the model.

---

##  Future Improvements

* Apply deep learning models
* Improve feature engineering
* Build a **Streamlit web application**
* Deploy the model for real-time predictions

---

##  Author

**Sunny Shirsath**

Machine Learning Enthusiast | Data Science Learner

---

## ⭐ Support

If you found this project useful, please consider **starring the repository** ⭐
