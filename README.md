
# 💳 **Credit Default Classification using Python & Azure ML Designer**

## 📌 **Project Overview**  
This project explores **credit card default prediction** using **classification models** in **Python and Azure Machine Learning Designer**. The objective is to predict whether a client will default on their credit card payment based on their **demographic and financial history**.

## 📂 **Dataset**  
- **Source:** UCI Machine Learning Repository  
- **Size:** 1,000+ samples with 24 features  
- **Description:** The dataset includes **demographic attributes, payment history, and default status**.  
- **Target Variable:** Binary classification label (**Defaulted: Yes/No**).  

---

## 🔍 **Methodology & Steps**  

### **1️⃣ Exploratory Data Analysis (EDA)**  
✔ Analyzed **dataset structure, missing values, and feature distributions** using histograms and pair plots.  
✔ **Standardized numerical features** using **StandardScaler** for better model performance.  
✔ Considered **ethical issues in credit scoring & fairness**.  

### **2️⃣ Data Preprocessing**  
✔ **Feature Engineering:** Selected important features and removed redundant ones.  
✔ **Data Normalization:** Applied **StandardScaler** for consistent feature scaling.  
✔ **Data Splitting:** Used `train_test_split` to split into **training and test sets**.  

### **3️⃣ Model Training & Hyperparameter Tuning**  
✅ **Logistic Regression**  
✅ **Random Forest Classifier**  

✔ Used **GridSearchCV & RandomizedSearchCV** for hyperparameter optimization.  

### **4️⃣ Model Evaluation**  
✔ Compared models using key metrics:  
   - ✅ **Accuracy**  
   - ✅ **Precision & Recall**  
   - ✅ **F1 Score**  
   - ✅ **Confusion Matrix**  

✔ Evaluated the performance of **Logistic Regression vs. Random Forest**.  
✔ Discussed business insights on how models can assist in **credit risk assessment**.  

### **5️⃣ Azure Machine Learning Designer Implementation**  
✔ Implemented **Logistic Regression & Decision Forest Classifier** in **Azure ML Designer**.  
✔ Compared **Azure ML (cloud-based) vs. Python (local implementation)** in terms of **scalability & performance**.  

---

## 🛠 **Technologies & Tools Used**  
- **Python:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn  
- **Machine Learning:** Logistic Regression, Random Forest, Decision Forest  
- **Cloud Platform:** Azure Machine Learning Designer  
- **Data Preprocessing:** StandardScaler, train_test_split  
- **Model Evaluation:** Confusion Matrix, F1 Score, Accuracy, Precision, Recall  

---

## 📌 **Conclusion & Business Insights**  
✔ **Random Forest outperformed Logistic Regression** after hyperparameter tuning.  
✔ **Feature selection & preprocessing** significantly improved model accuracy.  
✔ **Azure ML Designer** provides a **no-code scalable solution** for ML models.  
✔ **Business recommendations**: Improve **credit risk assessment strategies** for banks & financial institutions.  


