Banking Loan Approval Prediction System
📌 Project Overview

The Banking Loan Approval Prediction System is a Machine Learning project that predicts whether a loan application is likely to be approved or rejected based on applicant and loan-related information.

The project uses different classification algorithms and compares their performance using standard evaluation metrics.

🎯 Objectives
Predict loan approval using applicant and financial information.
Perform data preprocessing and handle missing values.
Analyze relationships between important features and loan approval.
Train multiple Machine Learning classification models.
Compare model performance using accuracy, precision, recall, F1-score, and confusion matrix.
📊 Dataset

The dataset contains 1,000 applicant records and 20 features related to loan applications.

Important features include:

Applicant Income
Coapplicant Income
Employment Status
Age
Marital Status
Dependents
Credit Score
Existing Loans
DTI Ratio
Savings
Collateral Value
Loan Amount
Loan Term
Loan Purpose
Property Area
Education Level
Gender
Employer Category
Loan Approval
Dataset Link

The dataset used in this project is available in the project repository:

View Dataset

If the dataset is not uploaded to the repository, this link will not work. Upload the dataset file to the same GitHub repository and use the filename banking_loan_dataset.csv.

🛠️ Technologies Used
Python
Jupyter Notebook
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Machine Learning
🤖 Machine Learning Models

The following classification algorithms are implemented:

Logistic Regression
K-Nearest Neighbors (KNN)
Gaussian Naive Bayes
🔄 Project Workflow
Dataset
   ↓
Data Loading
   ↓
Data Exploration
   ↓
Data Preprocessing
   ↓
Missing Value Handling
   ↓
Categorical Encoding
   ↓
Feature Scaling
   ↓
Train-Test Split
   ↓
Model Training
   ↓
Model Evaluation
   ↓
Model Comparison
🧹 Data Preprocessing

The project performs the following preprocessing steps:

Numerical missing values are handled using mean imputation.
Categorical missing values are handled using most-frequent imputation.
Applicant_ID is removed because it is an identifier.
Categorical features are encoded.
One-hot encoding is applied to relevant categorical variables.
Numerical features are standardized using StandardScaler.
The dataset is divided into training and testing sets using an 80:20 split.
random_state=42 is used for reproducibility.
📈 Exploratory Data Analysis

The project includes visual analysis of:

Loan approval distribution
Applicant income and loan approval
Credit score distribution
DTI ratio and loan approval
Correlation between numerical variables
Relationships between important features

The analysis helps identify patterns and relationships within the loan application data.

📏 Model Evaluation

The models are evaluated using:

Accuracy
Precision
Recall
F1-Score
Confusion Matrix

The performance of the different models is compared to understand their classification behavior on the test dataset.

▶️ How to Run the Project
1. Clone the repository
git clone YOUR_GITHUB_REPOSITORY_LINK
2. Open the project folder
cd Banking-Loan-Approval-Prediction-System
3. Install the required dependencies
pip install -r requirements.txt
4. Start Jupyter Notebook
jupyter notebook
5. Open the notebook

Open:

ShivamKumar_BankingLoanApprovalPredictionSystem.ipynb
6. Run the notebook

Run the notebook cells from top to bottom to reproduce the data preprocessing, analysis, model training, evaluation, and visualizations.

📁 Project Structure
Banking-Loan-Approval-Prediction-System/
│
├── ShivamKumar_BankingLoanApprovalPredictionSystem.ipynb
├── banking_loan_dataset.csv
├── requirements.txt
└── README.md
📌 Key Information
Project Type: Machine Learning / Classification
Dataset Size: 1,000 records
Number of Features: 20 columns
Target Variable: Loan_Approved
Train-Test Split: 80:20
Models: Logistic Regression, KNN, Gaussian Naive Bayes
👨‍💻 Author

Shivam Kumar

B.Tech Electrical & Computer Engineering
Kurukshetra University
