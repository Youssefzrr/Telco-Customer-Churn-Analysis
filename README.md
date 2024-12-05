
 ## Telco Customer Churn Analysis and Prediction

 This notebook analyzes customer churn data from a telecommunications company and builds machine learning models to predict customer churn.
 
 ### Quick Start
 ```bash
 git clone https://github.com/yourusername/telco-churn-analysis.git
 cd telco-churn-analysis
 pip install -r requirements.txt
 jupyter notebook
 ```
 
 ### Dataset
 The dataset contains customer information including:
 - Demographics (gender, senior citizen status)
 - Account information (tenure, contract type, payment method)
 - Services (phone, internet, additional features)
 - Billing (monthly charges, total charges)
 - Churn status
 
 ### Analysis Performed
 - Exploratory data analysis
 - Feature engineering and preprocessing
 - Model training and evaluation using:
   - Decision Trees
   - Random Forest
   - AdaBoost 
   - Gradient Boosting
   - XGBoost
   - Support Vector Machines
   - Logistic Regression
 
 ### Key Findings
 - AdaBoost achieved best performance with 84% accuracy
 - Most important churn factors:
   - Contract type
   - Customer tenure
   - Monthly charges
   - Service types
 
 ### Requirements
 Listed in requirements.txt:
 - Python 3.x
 - pandas
 - numpy 
 - scikit-learn
 - seaborn
 - matplotlib
 - jupyter
 
