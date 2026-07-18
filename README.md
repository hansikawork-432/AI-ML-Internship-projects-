# AI/ML Internship Projects

This repository contains a collection of predictive systems developed during my AI/ML internship at **InternPe**. The projects leverage various machine learning algorithms to solve diverse predictive modeling problems, ranging from healthcare analytics to sports and finance forecasting.

---

## Disclaimer & Terms of Use

> [!WARNING]
> **Educational & Research Purposes Only**
> 
> * **No Clinical or Medical Use:** The healthcare models included in this repository (such as the Breast Cancer Detection System and Diabetes Prediction System) are developed strictly for educational and academic exploration. They **must not** be used as a substitute for professional medical advice, diagnosis, screening, or clinical decision-making. 
> * **No Commercial Use:** These projects are not intended, certified, or optimized for commercial deployment or production environments.
> * **Data Source:** The datasets utilized across these projects were provided by **InternPe** or sourced from public open-source repositories on **Kaggle**. The data may be synthetic, anonymized, or outdated, and should not be used to infer real-world statistical baselines.
> 
> The author assumes no liability for any decisions made based on the predictions or code provided in this repository.

---

## Project Overview

The repository consists of five standalone Jupyter Notebooks:

### 1. Healthcare & Diagnostics
* **[Breast Cancer Detection System](Breast_cancer_detection_system_using_machine_learning.ipynb)**
  * **Objective:** Classify tumors as malignant or benign based on diagnostic features.
  * **Approach:** Standard data preprocessing, feature scaling, and binary classification using Machine Learning.
* **[Diabetes Prediction System](DIABETES_PREDICTION_USING_ML_WITH_PYTHON.ipynb)**
  * **Objective:** Predict the likelihood of a patient having diabetes based on clinical metrics (e.g., Glucose levels, BMI, Age).
  * **Approach:** Exploratory Data Analysis (EDA) and predictive classification implemented in Python.

### 2. Regression & Forecasting
* **[IPL 1st Inning Score Prediction](IPL_1st_Inning_Score_Prediction_using_Machine_Learning.ipynb)**
  * **Objective:** Predict the final first-innings score of an IPL cricket match dynamically using live match constraints.
  * **Approach:** Time-series/sequence-based regression factoring in current runs, wickets, overs, and team matchups.
* **[Car Price Prediction](Car%20price%20prediction%20using%20machine%20learning_BY_Hansika.ipynb)**
  * **Objective:** Estimate the resale value of used cars using features like vehicle age, mileage, fuel type, and brand.
  * **Approach:** Supervised regression modeling to optimize pricing accuracy.

### 3. Natural Language Processing (NLP)
* **[Spam Mail Detection](Spam_Mail_detection.ipynb)**
  * **Objective:** Classify incoming emails into 'Spam' or 'Ham' (Legitimate).
  * **Approach:** Text preprocessing, vectorization (such as TF-IDF), and classification algorithms.

---

## Built With

* **Language:** Python 3
* **Environment:** Google Colab / Jupyter Notebook
* **Core Libraries:** 
  * Data Manipulation: `pandas`, `numpy`
  * Data Visualization: `matplotlib`, `seaborn`
  * Machine Learning: `scikit-learn`

---

## License

This project is licensed under the [MIT License](LICENSE).
