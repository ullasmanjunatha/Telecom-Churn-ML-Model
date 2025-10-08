
---

## ⚙️ Models Used

The following models were trained and compared:

- Logistic Regression (Baseline)
- Decision Tree
- Random Forest
- Gradient Boosting
- **XGBoost (Base)**
- **XGBoost (Tuned – Final Model)**
- K-Nearest Neighbors (KNN)

---

## 📈 Model Evaluation Summary

| Model | Validation Accuracy | Test Accuracy | F1 Score |
|:------|:-------------------:|:--------------:|:--------:|
| Logistic Regression | 79% | 80% | 0.60 |
| Decision Tree | 80% | 79% | 0.59 |
| Random Forest | 80% | 79% | 0.59 |
| Gradient Boosting | 82% | 80% | 0.60 |
| **XGBoost (Base)** | **93%** | **81%** | **0.64** |
| **XGBoost (Model 3)** | **78%** | **76%** | **0.65** |
| KNN | 83% | 78% | 0.58 |

---

## 🏆 Final Model Selection

**Model 3 – Tuned XGBoost** was selected as the final model due to its:
- Excellent trade-off between precision and recall  
- Consistent validation and test performance  
- Avoidance of overfitting observed in the base model  
- Generalization ability for real-world telecom churn scenarios  

**Final Performance:**
- Validation Accuracy: **78.3%**
- Test Accuracy: **76.1%**
- F1 Score: **0.65**

---

## 💡 Business Recommendations

1. Use the model to identify **high-risk customers** (churn probability > 0.55).  
2. Implement **retention campaigns** such as loyalty discounts or personalized offers.  
3. Focus on key churn drivers like **contract type**, **tenure**, and **monthly charges**.  
4. Integrate model predictions into the company’s **CRM system** for automated churn alerts.  
5. Continuously retrain the model using **updated customer data** to improve accuracy.

---

## 🧰 Tech Stack

- **Python 3.13**
- **Libraries:** pandas, numpy, scikit-learn, xgboost, matplotlib, seaborn
- **Tools:** Jupyter Notebook, Git, Excel
- **Model:** XGBoost Classifier (Tuned using RandomizedSearchCV)

---

## 📊 Visualizations

- Accuracy comparison bar chart  
- Precision, Recall, and F1-score comparison plots  
- Final model performance visualization  

---

## 📘 Report

A detailed Word report is included:  
📄 `Telecom_Customer_Churn_Final_Report.docx`  
It summarizes all models, evaluation metrics, reasoning behind model selection, and business insights.

---

## 👤 Author

**Ullas Manjunatha**  
Machine Learning & Data Analytics Enthusiast  
📧 [ullasmanjunatha@gmail.com](mailto:ullasmanjunatha@gmail.com)  
🔗 [GitHub Profile](https://github.com/ullasmanjunatha)
