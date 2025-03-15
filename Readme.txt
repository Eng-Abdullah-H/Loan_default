# Loan Default Prediction

##  Project Overview
This project aims to predict *loan default risk* using machine learning techniques. The dataset contains *255,347 records* with various financial and personal details of borrowers, allowing us to analyze key risk factors.

##  Dataset
- *Total Entries:* 255,347  
- *Features:* 18  
- *Target Variable:* Default (0 = No Default, 1 = Default)  
- *Key Columns:*
  - *Borrower Info:* Age, Income, Education, Employment Type, Marital Status
  - *Loan Details:* Loan Amount, Loan Term, Interest Rate, Loan Purpose
  - *Credit History:* Credit Score, Number of Credit Lines, Debt-to-Income (DTI) Ratio
  - *Other Factors:* Has Mortgage, Has Dependents, Has Co-Signer

*Dataset Source:* (kaggle)

##  Approach
1. *Data Cleaning & Preprocessing:* Handling missing values, encoding categorical variables, and normalizing numerical features.
2. *Exploratory Data Analysis (EDA):* Identifying key trends, correlations, and visualizing distributions.
3. *Feature Engineering:* Creating new variables to enhance model performance.
4. *Model Selection & Training:* Evaluating multiple models and optimizing hyperparameters.
5. *Performance Evaluation:* Using accuracy, precision, recall, F1-score, and ROC-AUC to assess the model.

##  Technologies Used
- *Programming Language:* Python
- *Libraries:* Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, XGBoost

##  How to Run the Project
1. Clone the repository:
   bash
   git clone https://github.com/Eng-Abdullah-https://github.com/Eng-Abdullah-H/Loan_default.git
   
2. Navigate to the project directory:
   bash
   cd Loan_default
   
3. Install dependencies:
   bash
   pip install -r requirements.txt
   
4. Run the Jupyter Notebook to explore the analysis and predictions.

##  Results & Insights
- The best-performing model achieved *[91.49]% accuracy* with *[95.98]% ROC-AUC score*.

##  Future Work
- Implementing deep learning models for better performance.
- Exploring additional features for enhanced risk prediction.
- Deploying the model using Flask or FastAPI.

##  License
This project is for educational purposes. Feel free to use or modify it with proper attribution.

---
 *Connect with me:*  
[GitHub](https://github.com/Eng-Abdullah-H) | [Kaggle](https://www.kaggle.com/engabdullahhegazy)