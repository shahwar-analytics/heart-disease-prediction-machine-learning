
# ❤️ Heart Disease Prediction using Machine Learning

## 📌 Overview
Heart disease is one of the leading causes of death worldwide. Early detection is critical to prevent severe health complications and improve patient outcomes.

This project builds a machine learning system to predict the risk of heart disease using clinical patient data such as age, cholesterol, blood pressure, and heart rate. The goal is to identify patterns in the data and support early diagnosis and decision-making in healthcare.

---

## 🎯 Objectives
- Analyze and understand heart disease dataset features  
- Perform data cleaning and preprocessing  
- Explore data using visualizations  
- Train and compare multiple machine learning models  
- Evaluate models using accuracy, precision, recall, and F1-score  
- Identify key features influencing heart disease prediction  

---

## 📊 Dataset
- Source: Kaggle (Heart Disease Dataset) :contentReference[oaicite:0]{index=0}  
- Records: 270 patients  
- Features: 13 input variables + 1 target variable  
- Target:
  - `1` → Heart Disease Present  
  - `0` → No Heart Disease  

Key features include:
- Age  
- Sex  
- Chest pain type  
- Blood pressure  
- Cholesterol  
- Maximum heart rate  
- Exercise-induced angina  

---

## ⚙️ Technologies Used
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  

---

## 🔄 Workflow
1. Data Collection (Kaggle dataset)  
2. Data Cleaning (handling duplicates, formatting columns)  
3. Data Preprocessing (feature scaling using StandardScaler)  
4. Exploratory Data Analysis (EDA)  
5. Train-Test Split (80% training, 20% testing)  
6. Model Training  
7. Model Evaluation & Comparison  

---

## 📊 Data Visualization
The dataset was explored using multiple visualizations:

- Age distribution shows most patients are between 40–65 years  
- Cholesterol levels indicate variability across patients  
- Heart disease distribution shows class balance  
- Correlation heatmap highlights relationships between variables  

👉 As shown in the report (pages 6–9), features like **maximum heart rate, chest pain type, and ST depression** show strong relationships with heart disease.

---

## 🤖 Machine Learning Models

### 1. Logistic Regression
- Accuracy: **90.74%**
- Strong balance across precision, recall, and F1-score  
- Best overall model for this dataset  

---

### 2. Decision Tree
- Accuracy: **72.22%**
- Easy to interpret  
- Lower performance due to overfitting  

---

### 3. K-Nearest Neighbors (KNN)
- Optimal K = 12  
- Accuracy: **90.74%**
- High precision (100%) but lower recall for disease cases  

---

## 📈 Model Comparison

| Model               | Accuracy | Precision | Recall | F1 Score |
|--------------------|----------|----------|--------|----------|
| Logistic Regression | 90.74%  | 91.18%   | 93.94% | 92.54%   |
| Decision Tree       | 72.22%  | 76.47%   | 78.79% | 77.61%   |
| KNN (K=12)          | 90.74%  | 86.84%   | 100%   | 92.96%   |

👉 Logistic Regression provides the most balanced and reliable performance.

---

## 🔍 Key Insights
- Machine learning can effectively predict heart disease risk  
- Logistic Regression performs best due to balanced metrics  
- KNN shows strong precision but misses some cases (false negatives)  
- Important features:
  - Thalassemia type  
  - Number of major vessels  
  - Chest pain type  
  - ST depression (oldpeak)  

---

## 🧠 Results
- Both Logistic Regression and KNN achieved **~90.7% accuracy**  
- Decision Tree underperformed compared to other models  
- Feature importance aligns with real-world medical knowledge  

---

## ⚠️ Limitations
- Small dataset (270 records)  
- Single data source  
- No cross-validation applied  
- Slight class imbalance  

---

## 🚀 Future Improvements
- Use larger and more diverse datasets  
- Apply advanced models (Random Forest, Gradient Boosting)  
- Use cross-validation for better evaluation  
- Reduce false negatives (critical in healthcare)  
- Build a deployment app (Streamlit / Flask)  

---

## 💡 Conclusion
This project demonstrates that machine learning can effectively support early detection of heart disease using clinical data.

Logistic Regression emerges as the most reliable model, offering high accuracy and balanced performance, making it suitable for real-world healthcare decision support.

---

## 👤 Author
Mohammed Shahwar Ahmed
