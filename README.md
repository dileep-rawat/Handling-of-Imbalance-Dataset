# Handling Imbalanced Data in Machine Learning  

This repository demonstrates various resampling techniques to address class imbalance and evaluates their impact on model performance using **Logistic Regression, Random Forest, and XGBoost**.  

---

## 📊 Quick Takeaways (from the experiments in this notebook)

| Model                | Best Performing Techniques*                         | Notes                                                                 |
|-----------------------|-----------------------------------------------------|----------------------------------------------------------------------|
| Logistic Regression   | **SMOTE, SMOTE+ENN**                                | Balanced performance with higher recall, reducing bias to majority.  |
| Random Forest         | **SMOTE+Tomek, ENN**                                | Hybrid/cleaning methods improved generalization.                      |
| XGBoost              | **ADASYN, SMOTE+Tomek**                             | Benefited most from oversampling + hybrid approaches.                 |

\*Results may vary with dataset characteristics; these are indicative trends observed in this demo.  

---

## 🚀 How to Use  
1. Clone this repo  
2. Install dependencies (`requirements.txt`)  
3. Run the Jupyter notebook to reproduce experiments  
