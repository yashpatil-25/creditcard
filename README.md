🛡️ Credit Card Fraud Detection

A machine learning project focused on detecting fraudulent credit card transactions using real-world data. This project explores both supervised and unsupervised approaches, supported with proper data preprocessing and model evaluation techniques.

🔍 Features & Techniques

Dataset: creditcard.csv — contains transaction data including anonymized features and class labels (fraudulent or not).

Data Preprocessing:

Handled null values and removed duplicate entries.

Used boxplots for outlier detection and feature distribution analysis.

Applied StandardScaler for scaling features like Time and Amount.

Stratified train-test split for balanced evaluation.

🤖 Machine Learning Models Applied
| Algorithm                        | Type         | Notes                                                            |
| -------------------------------- | ------------ | ---------------------------------------------------------------- |
| **K-Nearest Neighbors (KNN)**    | Supervised   | Used `n_neighbors=5`, accuracy evaluated post-scaling.           |
| **K-Means Clustering**           | Unsupervised | Clustering anomaly detection; compared clusters with true class. |
| **Decision Tree Classifier**     | Supervised   | Simple and interpretable; evaluated with accuracy.               |
| **Random Forest Classifier**     | Supervised   | Ensemble of decision trees, robust to overfitting.               |
| **Support Vector Machine (SVM)** | Supervised   | Good for high-dimensional data; trained on scaled features.      |


📊 Evaluation
Used Accuracy Score to measure model performance.

Visual analysis via boxplots for each model to observe feature distribution and detect anomalies.

📁 Notebooks
Each model is implemented and evaluated in its own Jupyter Notebook:

KNNcreditcard.ipynb

K Means.ipynb

Desiontreecreditcard.ipynb

Randomforestcreditcard.ipynb

SVM.ipynb

📌 How to Run
Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/credit-card-fraud-detection.git
cd credit-card-fraud-detection
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt

Run the notebooks in Jupyter or VS Code.
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

