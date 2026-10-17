# Telco_Customer_Churn_EDA

Telco Customer Churn Analysis (EDA)

Project Overview :
This project explores customer churn in a telecommunications dataset using Python. Exploratory Data Analysis (EDA) and visualizations are used to understand customer characteristics, service subscriptions, contract types, tenure, and payment methods associated with churn.

Tools & Libraries :
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
  
Dataset :
The notebook uses Telco-Customer-Churn.csv, containing customer demographics, telecom services, contract details, billing information, and churn status.

Work Performed :
- Inspected dataset structure and summary statistics.
- Checked missing values and duplicate records.
- Converted TotalCharges to a numeric data type and replaced blank values with zero.
- Converted SeniorCitizen values into readable Yes/No labels.
- Visualized churn counts and the overall churn percentage.
- Compared churn across gender, senior-citizen status, tenure, and contract type.
- Created service-wise count plots for PhoneService, MultipleLines, InternetService, OnlineSecurity, OnlineBackup, DeviceProtection, TechSupport, StreamingTV, and StreamingMovies.
- Compared churn across payment methods.
  
Key Findings :
- Approximately 26.54% of customers have churned in the dataset.
- Customers with shorter tenure, especially those in their first one or two months, show a stronger tendency to churn.
- Month-to-month contract customers show more churn than customers with one-year or two-year contracts.
- Fiber-optic internet customers account for a notably high number of churn cases.
- Customers without Online Security or Tech Support show higher churn counts than customers who have these services.
- Electronic-check users show a higher tendency to churn than users of other payment methods.
  
Note: Most charts in the notebook show customer counts. Churn rates calculated within each category are recommended for fair comparisons because category sizes differ.

Business Recommendations :
- Improve onboarding and support for new customers.
- Explore incentives for longer-term contracts.
- Investigate customer satisfaction and service issues among fiber-optic users.
- Evaluate whether security and technical-support bundles could help improve retention.
- Review the payment experience for electronic-check users.
- Monitor churn rates by customer segment over time.
  
Conclusion :
This EDA highlights customer segments and service characteristics worth investigating to improve retention. The findings provide a starting point for further statistical analysis and building a machine-learning model to predict customers who may churn.

How to Run :
1. Download or clone this project.
2. Place Telco-Customer-Churn.csv in the same directory as the notebook.
3. Install the required libraries:  pip install pandas numpy matplotlib seaborn jupyter
4. Open and run Telco_Customer_Churn_EDA.ipynb in Jupyter Notebook.
