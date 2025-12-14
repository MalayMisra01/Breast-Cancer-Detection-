🩺 Breast Cancer Prediction using Machine Learning
A machine learning project built to classify breast tumors as Malignant or Benign using the popular Breast Cancer Wisconsin Dataset. This project includes data preprocessing, EDA, feature engineering, model training, evaluation, and prediction—implemented in Jupyter Notebook.

📁 Project Structure
├── Breast_Cancer_Prediction.ipynb     # Main notebook (your uploaded file)
├── README.md                          # Project documentation
├── data/                              # Dataset (if added)
└── models/                            # Saved models (optional)
🎯 Objective
To build and evaluate machine learning models that can accurately predict whether a tumor is malignant or benign, helping in early cancer diagnosis.

📊 Dataset
Source: Breast Cancer Wisconsin Diagnostic Dataset

Samples: 569

Features: 30 numeric features

Target:

0 → Malignant
1 → Benign
🛠️ Technologies Used
Python
NumPy
Pandas
Matplotlib / Seaborn
Scikit-Learn
Jupyter Notebook
📚 Workflow
✔️ 1. Data Loading
Import dataset and inspect structure.

✔️ 2. Exploratory Data Analysis (EDA)
Distribution plots
Correlation heatmap
Checking missing values
✔️ 3. Data Preprocessing
Label Encoding
Train-test split
Feature Scaling (StandardScaler)
✔️ 4. Model Training
Models commonly used:

Logistic Regression
K-Nearest Neighbors
Decision Tree
Random Forest
Support Vector Machine
✔️ 5. Model Evaluation
Evaluation metrics include:

Accuracy Score
Confusion Matrix
Classification Report
✔️ 6. Prediction
Model predicts tumor type for new data input.

📈 Results
Achieved high accuracy (80–98%) depending on model and parameters.
Best-performing model typically: Random Forest or SVM.
(You can replace this with your exact results if you want.)

▶️ How to Run This Project
Clone the repository:

git clone https://github.com/your-username/your-repo-name.git
Install required libraries:

pip install -r requirements.txt
Open Jupyter Notebook:

jupyter notebook
Run Breast_Cancer_Prediction.ipynb.
