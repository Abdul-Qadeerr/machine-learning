# Model Evaluation

## Definition
Model evaluation is the process of checking **how well a trained ML model performs** on new/unseen data.  

---
 
## Importance
- Prevents **overfitting** (model memorizing training data instead of generalizing).  
- Ensures model works in real-world scenarios.  

---

## Common Metrics
### For Classification
- Accuracy (overall correct predictions)  
- Precision (how many predicted positives were actually positive)  
- Recall (how many actual positives were detected)  
- F1-score (balance between precision and recall)  

### For Regression
- Mean Absolute Error (MAE)  
- Mean Squared Error (MSE)  
- R² Score (goodness of fit)  

---

## Techniques
- **Train/Test Split** (e.g., 80% training, 20% testing).  
- **Cross-validation** (training on multiple splits to avoid bias).  

---

## Real-life Examples
- **Credit Card Fraud Detection:** High recall is crucial to detect rare fraud cases.  
- **Medical Diagnosis:** Cancer detection models must have high recall (to detect as many patients as possible).  
- **Recommendation Systems:** Evaluating how many suggested movies a user actually likes.  

---
