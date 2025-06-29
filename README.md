# 🛡️ Credit Card Fraud Detection

A machine learning project aimed at detecting fraudulent credit card transactions using real-world data. This project involved data cleaning, feature scaling, model training, and performance evaluation.

---

## 🔍 Features and Techniques Applied

### 📁 Dataset Handling

* Loaded `creditcard.csv` using **pandas**
* Checked for **null values** and removed **duplicate rows**
* Used **boxplot** to visualize potential outliers

### 🧹 Data Preprocessing

* Split data into `X` (features) and `y` (target)
* Performed **train-test split** with `stratify=y`
* Applied **StandardScaler** to normalize `Time` and `Amount` features

### 🤖 Machine Learning Models

Applied and evaluated five algorithms (used **boxplot** prior to each for outlier analysis):

1. **K-Nearest Neighbors (KNN)**

   * Supervised classification
   * `n_neighbors=5`
   * Boxplot analysis before training

2. **K-Means Clustering**

   * Unsupervised anomaly detection
   * Compared cluster labels to true `Class`
   * Boxplot used to assess cluster patterns

3. **Random Forest Classifier**

   * Ensemble method using decision trees
   * Boxplot used for initial feature distribution check

4. **Support Vector Machine (SVM)**

   * Effective in high-dimensional space
   * Boxplot used to evaluate scaled feature ranges

5. **Decision Tree Classifier**

   * Fast and interpretable model
   * Boxplot applied to detect skewed feature values

### 📏 Evaluation Metrics

* Used **accuracy score** for initial evaluation

---
