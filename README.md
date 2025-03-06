# Breast-Cancer-Classification-Using-Machine-Learning

![Breast Cancer AI](https://upload.wikimedia.org/wikipedia/commons/thumb/5/5a/Breast_Cancer_Awareness_Pink.svg/1024px-Breast_Cancer_Awareness_Pink.svg.png)  

## 📖 **Overview**  
This project applies **machine learning** techniques to classify breast cancer cases as **malignant or benign** using various algorithms. The goal is to improve diagnostic accuracy and provide insights into model performance across key evaluation metrics.  

## 📊 **Models Used**  
✔ **XGBoost**  
✔ **Random Forest**  
✔ **Decision Tree**  
✔ **K-Nearest Neighbors (KNN)**  
✔ **Naïve Bayes**  
✔ **Logistic Regression**  
✔ **Support Vector Machine (SVM)**  

## 📂 **Dataset**  
The dataset used for this project is based on **breast cancer diagnostic data**, containing features such as tumor size, texture, and compactness.  

## 🏆 **Results Summary**  

| Model               | Accuracy | F1-Score | Precision | Recall  | Balanced Accuracy |
|---------------------|----------|----------|-----------|---------|------------------|
| **XGBoost**        | 98.24%   | 0.9736   | 1.0000    | 0.9487  | 0.9743          |
| **Random Forest**  | 97.36%   | 0.9610   | 0.9737    | 0.9487  | 0.9677          |
| **Decision Tree**  | 95.61%   | 0.9382   | 0.9048    | 0.9744  | 0.9605          |
| **Naïve Bayes**    | 95.61%   | 0.9315   | 1.0000    | 0.8718  | 0.9359          |
| **KNN**            | 94.74%   | 0.9189   | 0.9714    | 0.8718  | 0.9292          |
| **Logistic Regression** | 94.74% | 0.9167   | 1.0000    | 0.8462  | 0.9231          |
| **SVM**            | 92.98%   | 0.8857   | 1.0000    | 0.7949  | 0.8974          |

## 🔬 **Key Takeaways**  
✅ **XGBoost & Random Forest** provided the highest accuracy and F1-score, making them ideal for structured medical datasets.  
✅ **Naïve Bayes & Logistic Regression** demonstrated high precision but slightly lower recall, highlighting potential malignant case misclassifications.  
✅ **SVM** required fine-tuning to improve recall while maintaining high precision.  

### 🔍 **Key Checks to Ensure Results Are Valid**
- **Class Distribution:** If the dataset is **imbalanced**, check if the models are biased toward the majority class.
- **Cross-validation:** Ensure results are consistent across multiple train-test splits.
- **ROC-AUC Score:** If your dataset is balanced, a score above **0.95** confirms strong performance.

### 🛠 **Next Steps to Improve Performance**
- **Hyperparameter tuning:** Try Grid Search or Random Search for SVM and Decision Tree.
- **Feature Engineering:** Experiment with PCA or feature selection to remove redundancy.
- **Ensemble Methods:** Combine models using stacking to improve generalization.
