# Task-16-Hyperparameter-Tuning-using-GridSearchCV
# AI & ML Internship - Task 16  
## Hyperparameter Tuning using GridSearchCV (Breast Cancer Dataset)

### 📌 Task Objective
The goal of this task is to perform **hyperparameter tuning** using **GridSearchCV** to improve a machine learning model’s performance.  
A tuned model is then compared with the default model using evaluation metrics.

---

### 📂 Dataset Used
- **breast-cancer.csv**
- Target column is automatically detected (example: `diagnosis`)
- If target values are categorical (M/B), they are encoded into numeric format.

---

### 🛠 Tools & Libraries Used
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Joblib  

---

### ✅ Model Selected
For this task, the following model was used:

- **Support Vector Machine (SVM)**

---

### ⚙️ Workflow Steps Followed
1. Load dataset  
2. Apply basic preprocessing (drop nulls, remove unnamed columns)  
3. Split data into training and testing sets  
4. Train a **default SVM model**
5. Define a parameter grid for tuning  
6. Apply **GridSearchCV** with 5-fold cross-validation  
7. Extract best parameters and best trained model  
8. Compare performance of:
   - Default SVM
   - Tuned SVM (GridSearchCV)
9. Save the best tuned model pipeline  

---

### 🔍 Parameter Grid Used
The following hyperparameters were tuned:

- `kernel`: linear, rbf  
- `C`: 0.1, 1, 10, 100  
- `gamma`: scale, 0.01, 0.1, 1  

---

### 📊 Evaluation Metrics
Both models were evaluated using:

- Accuracy  
- Precision  
- Recall  
- F1 Score  

---

### 📌 Deliverables
✅ Best parameters output  
✅ Performance comparison table  
  

---
