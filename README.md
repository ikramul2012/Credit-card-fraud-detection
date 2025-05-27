
---



##  Machine Learning Models Used

The following models were implemented and evaluated for fraud detection performance:

| Model                          | Description |
|-------------------------------|-------------|
| **Logistic Regression**        | A baseline linear classifier often used for binary classification problems. |
| **Random Forest**              | An ensemble learning method using multiple decision trees for improved accuracy and robustness. |
| **XGBoost**                    | A high-performance gradient boosting algorithm known for its efficiency and accuracy. |
| **Neural Network (MLP)**       | A classic feedforward neural network trained using backpropagation. |
| **Deep Learning Model (Keras)**| A multi-layered deep neural network implemented using the Keras API. |
| **LSTM Model**                 | A Long Short-Term Memory network designed to capture sequence-based patterns in transaction data. |

These models were selected to provide a strong mix of traditional machine learning techniques and deep learning methods, enabling a robust comparison and selection of the best model.



---

## 📈 Evaluation Metrics

Each model is evaluated using:
- **Confusion Matrix**
- **Precision**
- **Recall**
- **F1-Score**
- **Accuracy**

🏆 **Best model** is chosen based on the **highest F1-Score**, which balances false positives and false negatives.

---

## Results

The following table summarizes the performance of all tested models using key classification metrics:

| Model                         | Accuracy | Precision | Recall   | F1-Score |
|------------------------------|----------|-----------|----------|----------|
| **XGBoost**                  | 0.9500   | 0.9618    | 0.9152   | **0.9379** |
| LSTM Model                   | 0.9425   | 0.9551    | 0.9030   | 0.9283   |
| Random Forest                | 0.9400   | 0.9379    | 0.9152   | 0.9264   |
| Deep Learning Model (Keras)  | 0.9400   | 0.9548    | 0.8970   | 0.9250   |
| Neural Network (MLP)         | 0.9100   | 0.9272    | 0.8485   | 0.8861   |
| Logistic Regression          | 0.8850   | 0.9220    | 0.7879   | 0.8497   |

**Best Performing Model**:  
The **XGBoost model** outperformed all others with an **F1-score of 0.9379**, striking the best balance between precision and recall for fraud detection.

F1-Score is especially important in fraud detection where both **false positives and false negatives** carry significant costs.


---

##  Tech Stack

- Python
- Pandas, NumPy
- Scikit-learn
- Imbalanced-learn (SMOTE)
- XGBoost
- Seaborn, Matplotlib

---

## How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/your-username/credit-card-fraud-detection.git
   cd credit-card-fraud-detection
