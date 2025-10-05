# 🏥 End-to-End Medical Insurance Cost Prediction Project

## 🔍 Project Overview
This project focuses on developing an **intelligent machine learning system** that predicts individual **medical insurance costs** based on demographic and lifestyle factors.  
It provides a full end-to-end workflow — from **data preprocessing** and **feature engineering** to **model training**, **evaluation**, and **deployment** through an interactive **Gradio interface**.

The goal is to help insurance companies and individuals estimate potential insurance charges efficiently and accurately.

---

## ⚙️ Key Challenge: Modeling Non-Linear Relationships
The dataset contains a mix of **numerical** and **categorical** features, including:

- `age`
- `bmi`
- `region`
- `smoking status`
- `number of dependents`

The main challenge was capturing the **non-linear relationships** among these factors and their effect on insurance costs.

To overcome this, multiple regression algorithms were tested:
- **Linear Regression**
- **Random Forest Regressor**
- **XGBoost Regressor**

The final model was selected based on performance metrics such as:
- **R² Score**
- **Mean Absolute Error (MAE)**
- **Root Mean Squared Error (RMSE)**

---

## 🧠 Workflow Overview
1. **Data Cleaning & Preprocessing** – Handling missing values, encoding categorical variables, and normalizing features.  
2. **Exploratory Data Analysis (EDA)** – Visualizing trends between insurance charges and variables like age, BMI, and smoking habits using Matplotlib and Seaborn.  
3. **Feature Engineering** – Creating meaningful new variables to improve model accuracy.  
4. **Model Training** – Testing multiple regression models to find the best fit.  
5. **Model Evaluation** – Comparing results using R², MAE, and RMSE metrics.  
6. **Model Deployment** – Deploying the final trained model with **Gradio** for real-time user interaction.

---

## 🧰 Tools & Technologies
- **Python**
- **Scikit-learn**
- **XGBoost**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Joblib** (for model saving/loading)
- **Gradio** (for deployment)
- **Jupyter Notebook / Kaggle**
- **GitHub**

---

## 🚀 Features
- Predicts medical insurance costs accurately using user input.
- Interactive **Gradio interface** for testing predictions.
- Visualized insights into factors influencing insurance prices.
- Clean, modular, and well-documented codebase for scalability.

---

## 🖼️ Example Output (Gradio App)
Users can input data such as **age**, **BMI**, **smoker/non-smoker**, and **region**, then instantly receive a predicted **insurance cost estimate**.

---

## 📊 Model Evaluation Example
| Model | R² Score | MAE | RMSE |
|--------|-----------|------|------|
| Linear Regression | 0.74 | 4200 | 6100 |
| Random Forest | 0.87 | 2600 | 3900 |
| XGBoost | **0.89** | **2400** | **3600** |

---

## 🗂️ Project Structure
