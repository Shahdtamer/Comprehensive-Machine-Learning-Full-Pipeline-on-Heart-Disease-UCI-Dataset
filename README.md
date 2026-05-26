Comprehensive Machine Learning Full Pipeline on Heart Disease UCI Dataset 

A complete end-to-end Machine Learning pipeline for predicting heart disease using the UCI Heart Disease dataset.
This project covers data preprocessing, exploratory data analysis (EDA), dimensionality reduction, feature selection, supervised & unsupervised learning, hyperparameter tuning, and model evaluation.

 Project Overview

The goal of this project is to analyze patient health data and predict the likelihood of heart disease using multiple machine learning techniques.

The pipeline includes:

Data Cleaning & Preprocessing
Exploratory Data Analysis (EDA)
Feature Engineering & Selection
Principal Component Analysis (PCA)
Supervised Learning Models
Unsupervised Learning Models
Hyperparameter Optimization
Model Exporting
 Objectives
Clean and preprocess the Heart Disease dataset
Perform feature scaling and encoding
Apply PCA for dimensionality reduction
Select the most important features using statistical and ML methods
Train and evaluate multiple classification models
Discover hidden patterns using clustering algorithms
Optimize model performance using GridSearchCV & RandomizedSearchCV
Export the trained model for reuse
 Project Structure
Heart_Disease_Project/
│
├── data/
│   └── heart_disease.csv
│
├── notebooks/
│   ├── 01_data_preprocessing.ipynb
│   ├── 02_pca_analysis.ipynb
│   ├── 03_feature_selection.ipynb
│   ├── 04_supervised_learning.ipynb
│   ├── 05_unsupervised_learning.ipynb
│   └── 06_hyperparameter_tuning.ipynb
│
├── models/
│   └── final_model.pkl
│
├── results/
│   └── evaluation_metrics.txt
│
├── requirements.txt
├── README.md
└── .gitignore
🧠 Machine Learning Workflow
1️⃣ Data Preprocessing & Cleaning
Loaded dataset using Pandas
Handled missing values
Encoded categorical variables
Standardized numerical features
Performed Exploratory Data Analysis (EDA)
EDA Visualizations
Histograms
Correlation Heatmaps
Boxplots
Pairplots
2️⃣ Dimensionality Reduction (PCA)

Principal Component Analysis (PCA) was applied to reduce feature dimensionality while preserving the majority of the dataset variance.

PCA Tasks
Explained variance analysis
Cumulative variance visualization
PCA scatter plots
3️⃣ Feature Selection

Feature selection techniques used:

Recursive Feature Elimination (RFE)
Chi-Square Test
Random Forest Feature Importance

This helped improve model performance and reduce overfitting.

4️⃣ Supervised Learning Models

The following classification algorithms were trained and evaluated:

Model	Purpose
Logistic Regression	Baseline linear classifier
Decision Tree	Tree-based classification
Random Forest	Ensemble learning
Support Vector Machine (SVM)	Margin-based classification
Evaluation Metrics
Accuracy
Precision
Recall
F1-Score
ROC Curve
AUC Score
5️⃣ Unsupervised Learning
Clustering Algorithms
K-Means Clustering
Hierarchical Clustering
Tasks
Elbow Method Analysis
Dendrogram Visualization
Cluster Comparison with Actual Labels
6️⃣ Hyperparameter Tuning

Optimization techniques used:

GridSearchCV
RandomizedSearchCV

The best hyperparameters were selected based on model performance.

7️⃣ Model Export

The final trained model pipeline was saved using:

joblib.dump(model, "final_model.pkl")

This ensures reproducibility and easy reuse.

📊 Technologies Used
Programming Language
Python
Libraries & Frameworks
Pandas
NumPy
Scikit-learn
Matplotlib
Seaborn
Joblib
ML Techniques
PCA
RFE
Chi-Square Test
Logistic Regression
Decision Trees
Random Forest
SVM
K-Means Clustering
Hierarchical Clustering
⚙️ Installation
Clone Repository
git clone https://github.com/your-username/Heart_Disease_Project.git
cd Heart_Disease_Project
Create Virtual Environment
python -m venv venv
Activate Environment
Windows
venv\Scripts\activate
Linux / Mac
source venv/bin/activate
Install Dependencies
pip install -r requirements.txt
▶️ Usage
Run Jupyter Notebooks
jupyter notebook
📈 Results

The project successfully:

Built multiple ML classification models
Improved performance using feature selection and tuning
Reduced dimensionality using PCA
Detected hidden patterns using clustering
Exported the best performing trained model
📌 Dataset

Dataset Used:
Heart Disease UCI Dataset

🔮 Future Improvements
Add Deep Learning models using TensorFlow/Keras
Add Explainable AI techniques (SHAP/LIME)
Improve feature engineering methods
Compare additional ensemble models
Build a deployment-ready web application
