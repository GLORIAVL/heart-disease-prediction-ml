# Heart Disease Prediction using Machine Learning

Predicts the likelihood of heart disease in a patient using clinical parameters like age, blood pressure, cholesterol, chest pain type, etc.

## Tech Stack
- Python
- Jupyter Notebook
- Scikit-learn, Pandas, NumPy

## Dataset
UCI Machine Learning Repository — Heart Disease dataset (843 instances, 14 clinical attributes)

## Approach
- Data cleaning and preprocessing
- Exploratory Data Analysis (correlation heatmap, class balance check)
- Model training: Support Vector Machine, Random Forest, AdaBoost, Gradient Boosting
- Model evaluation using accuracy score, confusion matrix, classification report

## Results
| Model | Accuracy |
|---|---|
| SVM | 74% |
| AdaBoost | 91% |
| Gradient Boosting | 97% |
| **Random Forest** | **98% (best)** |

Random Forest Classifier gave the best performance for this dataset.
