# Breast-Cancer-Classification-Using-Machine-Learning

### ✅ **Observations from the Results**  
1. **XGBoost and Random Forest** performed the best, which is common since tree-based models work well on structured data.  
2. **SVM is slightly lower**, which might be due to improper hyperparameter tuning.  
3. **Naive Bayes has a perfect precision of 1.0**, likely classifying **all malignant cases correctly but missing some benign ones**, reducing recall.  
4. **Logistic Regression also has high precision but slightly lower recall**, which is expected since it's a simpler model.

### 🔍 **Key Checks to Ensure Results Are Valid**
- **Class Distribution:** If the dataset is **imbalanced**, check if the models are biased toward the majority class.
- **Cross-validation:** Ensure results are consistent across multiple train-test splits.
- **ROC-AUC Score:** If your dataset is balanced, a score above **0.95** confirms strong performance.

### 🛠 **Next Steps to Improve Performance**
- **Hyperparameter tuning:** Try Grid Search or Random Search for SVM and Decision Tree.
- **Feature Engineering:** Experiment with PCA or feature selection to remove redundancy.
- **Ensemble Methods:** Combine models using stacking to improve generalization.
