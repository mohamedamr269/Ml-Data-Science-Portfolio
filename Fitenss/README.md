# 🏋️ Fitness Project

## 📌 Overview
This project predicts whether a person is physically fit based on health and lifestyle factors such as age, height, weight, heart rate, blood pressure, sleep hours, nutrition quality, and activity level.  
It demonstrates the full data science workflow: from data preprocessing to machine learning modeling and deployment.

---

## 🎯 Objectives
- Clean and preprocess raw health data.  
- Perform exploratory data analysis (EDA) to identify key patterns.  
- Build machine learning models to predict fitness levels.  
- Compare model performance using metrics like Accuracy and F1-Score.  
- Deploy an interactive app using Streamlit.  

---

## ⚙️ Workflow
1. **Data Collection & Cleaning** – handled missing values, standardized columns.  
2. **Exploratory Data Analysis (EDA)** – visualized trends (e.g., relation between sleep, nutrition, and fitness).  
3. **Modeling** – tested Logistic Regression, Decision Tree, and Random Forest.  
4. **Evaluation** – compared models using accuracy and F1-Score.  
5. **Deployment** – built a Streamlit app for real-time predictions.  

---

## 📊 Tools and Libraries
- **Python**  
- **Pandas, NumPy** – data preprocessing and analysis  
- **Matplotlib, Seaborn** – data visualization  
- **Scikit-learn** – machine learning models  
- **Streamlit** – interactive web app  

---

## 📈 Results
- Logistic Regression: Accuracy = 82%, F1-Score = 0.79  
- Decision Tree: Accuracy = 85%, F1-Score = 0.81  
- Random Forest: Accuracy = 90%, F1-Score = 0.88  

✅ Random Forest achieved the best performance.  
✅ Clear link identified between **sleep, nutrition, and activity** with fitness level.  
✅ Detected high-risk patterns such as *low activity + poor nutrition*.  

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone <repository-link>
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the app:
   ```bash
   streamlit run app.py
   ```

---

## 💡 Future Improvements
- Use advanced models like Neural Networks.  
- Add more features (e.g., detailed diet, medical history).  
- Improve UI design in Streamlit for better user experience.  

---

## 📜 License
This project is for educational purposes. You are free to use and adapt it with proper attribution.  
