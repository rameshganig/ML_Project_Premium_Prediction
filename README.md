# ML_Project_Premium_Prediction
**Codebasics ML Course – Health Insurance Premium Prediction Project**

---

## 📘 Project Overview
This project aims to build a Machine Learning model to predict insurance premium amounts based on historical data and relevant features.  
The model includes data preprocessing, feature engineering, and predictive modeling techniques for accurate predictions.

here the Data is Split in to two category Yong and Rest, reson being the final model performance was afected by the yong <25 age when we built the model with over all data, so we analised that and concluded to split the data and process the data sepratly and built the individula models.

---

## ✨ Features
- Data Cleaning and Preprocessing
- Exploratory Data Analysis (EDA) with visualizations
- Feature Engineering for improved model performance
- Model Training using regression algorithms (Linear Regression, Random Forest, XGBoost, etc.)
- Model Evaluation using metrics like RMSE, MAE, and R²
- Model Export for deployment and integration

---

## 📊 Dataset
- **Source:** (Dataset was provided by the Trainer)  
- **Description:** The dataset contains customer information and factors affecting premium calculation, including:  
  - Age  
  - Gender  
  - Number of Dependants 
  - income in lakhs  
  - Genetical risk
  - Insurance Plan
  - Employment Status
  - Merital Status
  - BMI Category
  - Smoking Status
  - Region
  - MEdical History 

---

## 🚀 Getting Started

### 1️⃣ Clone the repository

To clone the repository, use the following command:

git clone https://github.com/your-username/ML_Project_Premium_Prediction.git

### 2️⃣ Install required Python libraries

To install all the required Python libraries, use the following command:

pip install -r requirements.txt

---
## 📁 File Structure

```
ML_Project_Premium_Prediction/
│
├── artifacts/             # Saved model files
├── notebooks/             # Jupyter notebooks for EDA and experiments
├── src/                   # Python scripts for preprocessing, training, and prediction
├── requirements.txt       # Python dependencies
├── README.md              # Project documentation
```
---

## 📸 Screenshots

![Dashboard View](artifacts/dashboard.png)
![Model Results](artifacts/model_results.png)