# AIML-intern-task-4
# Binary Classification with Logistic Regression

This project demonstrates a complete machine learning workflow using **Logistic Regression** on a binary classification dataset (`data.csv`), likely the Pima Indians Diabetes dataset.
---
## Project Workflow

1. **Load and Inspect Data**
2. **Preprocess:**
   - Drop missing or irrelevant features (if any)
   - Split data into features and target (`Outcome`)
   - Standardize features using `StandardScaler`
3. **Model Training**
   - Train Logistic Regression using `sklearn.linear_model`
4. **Evaluation**
   - Confusion Matrix
   - Precision, Recall, ROC-AUC
   - ROC Curve Visualization
5. **Threshold Tuning**
   - Adjust threshold from default `0.5` to custom values (e.g., `0.3`)
   - Evaluate effect on classification

---

## Metrics Used

- **Confusion Matrix**
- **Precision**
- **Recall**
- **ROC-AUC Score**
- **ROC Curve Plot**

## 🔬 Sigmoid Function
Logistic Regression maps predictions to probabilities using the sigmoid function:

\[
\sigma(z) = \frac{1}{1 + e^{-z}}
\]

Where `z` is a linear combination of the features. A classification threshold (usually 0.5) is used to convert this probability to class labels. You can adjust the threshold to tune precision/recall tradeoffs.


# Output Example
lua
Copy
Edit
Confusion Matrix:
[[85 15]
 [20 39]]
Precision: 0.722
Recall:    0.661
ROC-AUC:   0.82
