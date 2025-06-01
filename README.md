# Wine_quality_prediction
A machine learning project to predict wine quality based on physicochemical features using regression and classification models.
📊 Project Objective

To build and evaluate machine learning models that can predict wine quality scores (ranging from 0–10) based on features like acidity, sugar, pH, alcohol content, and more.

---

## 🛠️ Tech Stack

- **Python**
- **Pandas**, **NumPy** – Data manipulation
- **Matplotlib**, **Seaborn** – Data visualization
- **Scikit-learn** – ML modeling (Regression & Classification)

## 🧠 Models Used and Performance

| Model                  | Accuracy | Precision | Recall  | F1 Score |
|------------------------|----------|-----------|---------|----------|
| Logistic Regression    | 0.86875  | 0.600     | 0.26087 | 0.36364  |
| SVM (Linear)           | 0.85625  | 0.000     | 0.00000 | 0.00000  |
| SVM (RBF Kernel)       | 0.87500  | 0.71429   | 0.21739 | 0.33333  |
| Random Forest (n=100)  | 0.90313  | 0.74194   | 0.50000 | 0.59740  |

> 🔍 **Best Model:** Random Forest (Accuracy = 90.31%, F1 Score = 0.597)

find the dataset in winequality.csv file
