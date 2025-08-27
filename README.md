# Heart-Disease-Prediction-

# 🫀 Heart Disease Prediction  

A machine learning project that predicts the likelihood of heart disease in patients based on clinical and demographic features. The project demonstrates an end-to-end data science workflow — from **data preprocessing and visualization** to **model building and evaluation**.  

---

## 📌 Project Overview  
Heart disease is one of the leading causes of mortality worldwide. Early prediction can help in timely medical interventions and improved healthcare planning.  

In this project, I:  
- Performed **data cleaning** and **feature encoding**  
- Conducted **exploratory data analysis (EDA)** with visualizations  
- Built and compared multiple **machine learning models**  
- Evaluated models with accuracy, F1-score, ROC-AUC, and confusion matrix  

---

## 🛠️ Tech Stack  
- **Languages & Libraries**: Python, NumPy, Pandas, Matplotlib, Seaborn  
- **Machine Learning**: scikit-learn (Logistic Regression, Random Forest, etc.)  
- **Evaluation Metrics**: Accuracy, Precision, Recall, F1-score, ROC-AUC  

---

## 📊 Dataset  
- **Source**: `Heart_Disease_Prediction.csv`  
- Contains **clinical and demographic features** like age, gender, chest pain type, blood pressure, cholesterol, thallium stress test results, etc.  
- Target variable: `Heart Disease` (Presence = 1, Absence = 0)  

---

## 🔍 Exploratory Data Analysis (EDA)  
- Checked missing values and duplicates  
- Visualized outliers using **box plots**  
- Correlation heatmap to identify strong feature relationships  
- Feature-wise bar plots (e.g., Thallium vs Heart Disease)  

---

## 🤖 Model Building  
1. **Data Preprocessing**  
   - Label encoding for categorical features  
   - Standard scaling of numerical features  

2. **Models Implemented**  
   - Logistic Regression  
   - Random Forest Classifier  

3. **Train-Test Split**  
   - 75% training, 25% testing  

---

## 📈 Results  
- **Logistic Regression** achieved strong baseline performance  
- **Random Forest** improved accuracy and robustness  
- Final evaluation metrics included:  
  - Accuracy: ~90%  
  - Strong F1-score  
  - ROC-AUC demonstrating good classification capability  

---

## 🚀 How to Run  
1. Clone this repository  
   ```bash
   git clone https://github.com/Sai-Kumar159/Heart-Disease-Prediction-.git
   cd Heart-Disease-Prediction-

# Install dependencies
pip install -r requirements.txt

# Run the Jupyter notebook
jupyter notebook "Heart-disease-prediction (2).ipynb"

