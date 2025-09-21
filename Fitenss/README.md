# 🏋️ Fitness Project  

## 📌 Introduction  
The **Fitness Project** is a machine learning project designed to analyze and classify health and fitness-related data. The main goal is to build an intelligent system that predicts whether a person is *fit* (`is_fit`) based on various features such as age, height, weight, heart rate, blood pressure, sleep hours, nutrition quality, and activity level.  

---

## 🎯 Objectives  
1. **Data Cleaning**: Handle missing values, duplicates, and outliers.  
2. **Data Transformation**: Encode categorical variables and prepare data for modeling.  
3. **Feature Engineering**: Create new meaningful features such as:  
   - BMI  
   - Heart Rate to Age Ratio (`hr_age_ratio`)  
   - Sleep & Nutrition Score (`sleep_nutrition_score`)  
   - Smoke Impact on Blood Pressure (`smoke_impact`)  
4. **Exploratory Data Analysis (EDA)**: Visualize distributions, correlations, and relationships.  
5. **Feature Selection**: Use RFE, SFS, and Feature Importance to select the most relevant features.  
6. **Model Training**: Train and evaluate multiple algorithms (Logistic Regression, Decision Tree, Random Forest, Gradient Boosting, SVM, XGBoost, ANN).  
7. **Hyperparameter Tuning**: Optimize models using GridSearchCV.  
8. **Final Model Deployment**: Save the best-performing model for later use.  

---

## ⚙️ Workflow  
1. **EDA & Cleaning**: Inspect, clean, and preprocess the dataset.  
2. **Encoding**: Convert categorical variables into numerical format.  
3. **Feature Engineering**: Generate new features to improve predictive power.  
4. **Model Training**: Compare the performance of different machine learning algorithms.  
5. **Hyperparameter Tuning**: Fine-tune model parameters for better accuracy.  
6. **Final Model**: Choose Logistic Regression as the best-performing model and export it.  

---

## 📊 Results  
- Several models were tested, and **Logistic Regression** achieved one of the best performances after tuning.  
- The final model is stored as:  
  ```
  final LogisticRegression_model.pkl
  ```  

---

## 🚀 Future Work  
- Deploy the model in a **Streamlit app** for easy user interaction.  
- Integrate the model into health/fitness platforms to assist trainers and healthcare providers.  
- Expand the project with larger and more diverse datasets for improved generalization.  
