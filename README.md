
# Cardiac Arrest Prediction Model

This project uses machine learning to predict the likelihood of cardiac arrest in patients based on clinical features. Two models are implemented: **Logistic Regression** and **Random Forest**, with a focus on performance evaluation using key metrics and visualizations.

## Visualizations & Insights

### 1. Confusion Matrix

Confusion matrix for the Random Forest model on the test set:

- **True Positives (TP):** 101  
- **True Negatives (TN):** 89  
- **False Positives (FP):** 11  
- **False Negatives (FN):** 4  

**Insight:** The model correctly identifies most patients at risk of cardiac arrest, with minimal false negatives.

---

### 2. ROC Curve & AUC

- **Logistic Regression AUC:** 0.91  
- **Random Forest AUC:** 0.99  

**Insight:** Random Forest has a higher AUC, indicating better ability to distinguish between patients with and without cardiac arrest.

---

### 3. Feature Importance (Random Forest)

Top features influencing predictions:

- **cp:** Chest pain type  
- **thal:** Thalassemia  
- **ca:** Number of major vessels colored by fluoroscopy  

**Insight:** These clinical features are key predictors, helping clinicians focus on the most relevant indicators.

---

### 4. Model Comparison: Training vs Testing Accuracy

| Model               | Train Accuracy | Test Accuracy |
|--------------------|----------------|---------------|
| Logistic Regression | 0.82           | 0.80          |
| Random Forest       | 0.85           | 0.84          |

**Insight:** Random Forest shows higher accuracy and generalizes better on test data compared to Logistic Regression.

---

## Conclusion

The **Random Forest model** outperforms Logistic Regression in predicting cardiac arrest. This model can provide early warning insights, helping in timely clinical intervention and risk management.

## Dataset

The dataset used for this project is included in the repository (`/data/cardiac_arrest_dataset.csv`). 
# Cardiac Arrest Prediction Model

This project uses machine learning to predict the likelihood of cardiac arrest in patients based on clinical features. Two models are implemented: **Logistic Regression** and **Random Forest**, with a focus on performance evaluation using key metrics and visualizations.

---

## Dataset

The dataset used for this project is the **Cardiac Arrest Dataset** from Kaggle:  
Dataset source: [Cardiac Arrest Dataset on Kaggle](https://www.kaggle.com/datasets/leonidaskaragkounis/cardiac-arrest-dataset)

- **File used:** `cardiac arrest dataset.csv`  
