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

1. Decision Tree Classifie
![Screenshot 2025-06-29 195445](https://github.com/user-attachments/assets/1060ecb8-3ca4-4007-b681-bc0a3b16b3f6)
![Screenshot 2025-06-29 195929](https://github.com/user-attachments/assets/7b9bbb92-4e09-45e5-9564-78bea5dcc18e)

2. K-Means Clustering
![Screenshot 2025-06-29 200115](https://github.com/user-attachments/assets/76e040bb-d9af-4426-a056-41b473eaa2e4)

3.Random Forest Classifier
![Screenshot 2025-06-29 200329](https://github.com/user-attachments/assets/001e664f-8fc7-4c2c-be55-387be1bbcb21)

4. Support Vector Machine (SVM)
![Screenshot 2025-06-29 200520](https://github.com/user-attachments/assets/84cdd7c6-b84e-4c64-a642-8356cd00d30e)

5.K-Nearest Neighbors
![Screenshot 2025-06-29 203506](https://github.com/user-attachments/assets/f589e35b-b99e-4136-9905-47a22c42b3d8)

