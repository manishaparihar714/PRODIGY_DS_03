# PRODIGY_DS_03
Task 3:  Decision Tree Classifier Project using Python

This project demonstrates how to build and evaluate a **Decision Tree Classifier** using Python.  
The dataset is preprocessed, split into training and testing sets, and evaluated using **confusion matrix** and **accuracy score**.

---

## 🚀 Project Workflow
1. **Data Preprocessing**
   - Loaded dataset
   - Handled missing values (if any)
   - Encoded categorical variables
   - Train-test split

2. **Model Building**
   - Implemented **Decision Tree Classifier** from `sklearn`
   - Trained the model on training data

3. **Evaluation**
   - Plotted **confusion matrix**
   - Calculated **accuracy score**

---

## 📊 Confusion Matrix
The confusion matrix shows how well the model classified the samples.

- **True Negatives (TN):** 772  
- **False Positives (FP):** 29  
- **False Negatives (FN):** 75  
- **True Positives (TP):** 29  

🔎 **Accuracy** = (TP + TN) / Total Samples  

---

## ⚙️ Tech Stack
- Python 🐍
- Pandas, NumPy
- scikit-learn
- Matplotlib, Seaborn

---

## 📈 Results
- The model achieves a reasonable accuracy on the dataset.  
- Results show potential but can be improved with:
  - Hyperparameter tuning (e.g., max_depth, min_samples_split)
  - Feature engineering
  - Trying advanced models like Random Forests

---

