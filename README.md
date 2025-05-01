💳 Credit-Card-Fraud-Detection
A machine learning project that identifies fraudulent credit card transactions using supervised learning techniques. This project is based on a highly imbalanced dataset and demonstrates techniques to preprocess data, handle class imbalance, and build accurate classification models.
🔍 About
Credit card detection is a common problem where people make the unauthorized transactions using someone else's card. Because fraud happens in only a small number of casses compared to regular transactions, it's hard to detect. In this project, i use machine learning to help spot these rare frauds automatically. I worked with a real world data that from the kaggle that includes thousands of credit cards transactions, most of which are not fraud. To deal with this imbalance data , i used special techniques like SMOTE to balance the dataset before training the models. I tested different algorithms that are from machine learning like logistic regression, decision tree, random forest to see which one task is best. After comapring their performance, i found that the random forest gave the most accurate results, especilly in catching fraudulent transactions. This Projects Shows how machine learning can be powerful tool for improving the safety and security of digital parameters. 
## 🧰 Technologies Used
- Python 3.13
- NumPy & Pandas
- Scikit-learn
- Matplotlib & Seaborn
- Imbalanced-learn (SMOTE, etc.)
- Jupyter Notebook
🧠** Modeling Approach**
  Data Cleaning & Exploration (EDA)
  Feature Scaling (StandardScaler)
  Handling Imbalanced Data (SMOTE / Undersampling)
  Model Training:
  Logistic Regression
  Decision Tree
  Random Forest
**Model Evaluation:**
Confusion Matrix
Precision, Recall, F1-Score
ROC-AUC
📈 Results
Best performing model: Random Forest
Achieved:
High Recall (essential for minimizing false negatives)
ROC-AUC: ~0.97 (on test data)
