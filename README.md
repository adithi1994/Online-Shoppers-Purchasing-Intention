# Online-Shoppers-Purchasing-Intention
# 🛒 Online Shoppers Purchase Intention Prediction

This project analyzes behavioral data of online shoppers to predict whether a session will result in a purchase (Revenue = 1). It uses multiple machine learning algorithms to model customer intent based on page interactions, traffic sources, and visitor attributes.

## 📊 Dataset
- Source: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/online+shoppers+intention+dataset)
- Records: 12,330
- Features: Session durations, page interactions, bounce rates, month, visitor type, etc.

## 🔧 Key Steps

1. **Data Preprocessing**
   - Handled missing and malformed values
   - Applied cyclical encoding for `Month`
   - Log-transformed skewed columns
   - Standardized numerical features
   - Converted categorical features using one-hot encoding

2. **Feature Engineering**
   - SMOTE used to balance classes
   - Derived cyclical features: `Month_sin`, `Month_cos`

3. **Modeling**
   - Algorithms: Logistic Regression, Random Forest, SVM, KNN, Gradient Boosting, AdaBoost, Voting Classifier
   - Evaluated using: Accuracy, Precision, Recall, F1-Score, ROC-AUC
   - Cross-validation and hyperparameter tuning

4. **Unsupervised Learning**
   - PCA for dimensionality reduction
   - Clustering using KMeans, DBSCAN, and Agglomerative methods
   - Silhouette scores for validation

## 🧠 Results
- Best model(s): [To be filled based on your results]
- ROC-AUC achieved: [Insert ROC-AUC score]
- Insights: [E.g., Product-related duration and PageValues are strong predictors]

## 📁 Project Structure
- `Online_shoppers.ipynb` – Main Jupyter Notebook
- `online_shoppers_intention.csv` – Dataset
- `README.md` – Project overview
  
