🔬 Diabetes Prediction - Exploratory Data Analysis and Machine Learning
This project aims to build a machine learning model that predicts whether a person has diabetes based on medical diagnostic measurements. The dataset used is the Pima Indians Diabetes Database, which is publicly available on Kaggle.

🧪 What’s Included
Loading and previewing the dataset

Handling missing values and anomalies

Descriptive statistics and distribution visualizations

Correlation matrix analysis

Identification and handling of invalid zero values (e.g., Glucose = 0)

Data cleaning and preprocessing

Model training and evaluation with various algorithms

📊 Dataset Information
Source: Kaggle - Pima Indians Diabetes Database

Size: 768 rows × 9 columns

Target variable: Outcome (0 = Not diabetic, 1 = Diabetic)

🧰 Tech Stack
Python 3.8+

Jupyter Notebook

pandas, numpy

seaborn, matplotlib

scikit-learn

🧠 Models Used
We trained and evaluated the following supervised learning models:

Logistic Regression

Support Vector Machine (SVM)

Random Forest Classifier

K-Nearest Neighbors (KNN)

Each model was evaluated using accuracy score, confusion matrix, and classification report.

📂 Project Structure

📁 diabetes-prediction/
├── exploration.ipynb          # Exploratory Data Analysis (EDA)
├── cleaning_and_model.ipynb   # Data cleaning and model training
├── diabetes.csv               # Original dataset
├── diabetes_cleaned.csv       # Cleaned dataset after preprocessing
└── README.md                  # Project documentation
🚀 How to Run
Clone the repository

Install dependencies


pip install -r requirements.txt
Open the notebooks and run cells in order:

exploration.ipynb

cleaning_and_model.ipynb

