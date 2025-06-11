# Credit Exploratory Data Analysis (EDA)

##  Project Overview
This project involves analyzing historical loan application data to understand consumer and loan characteristics that influence the risk of default. The goal is to help a consumer finance company improve its loan approval strategy by identifying patterns and reducing both financial loss and missed business opportunities.

##  Business Context
Loan providers face two main risks:
-  Approving a loan to a potential defaulter → leads to **financial loss**.
-  Rejecting a loan to a trustworthy applicant → results in **missed revenue**.

By performing **exploratory data analysis (EDA)** on consumer data, we aim to:
- Distinguish high-risk applicants from low-risk ones
- Identify important applicant features and past behavior patterns
- Inform better decision-making in loan approvals

## Dataset Description
The dataset consists of three CSV files:

1. **`application_data.csv`**
   - Client demographics and financial data at time of loan application
   - Label for payment difficulty (default indicator)

2. **`previous_application.csv`**
   - Data on client's previous loan applications
   - Includes final decision: Approved, Cancelled, Refused, or Unused offer

3. **`columns_description.csv`**
   - Data dictionary explaining the variables in the dataset

##  Tools & Technologies Used
- **Python (Pandas, NumPy)** – data manipulation and analysis  
- **Matplotlib & Seaborn** – data visualization  
- **Jupyter Notebook** – interactive analysis  
- **Google Drive / Google Colab** – data access and execution

##  Key EDA Objectives
-  Explore client attributes (age, income, employment, credit history)  
-  Analyze loan attributes (amount, duration, repayment rate, purpose)  
-  Investigate previous application outcomes and behavior patterns  
-  Visualize correlation between features and default risk  
-  Compare approved vs. defaulted client profiles  

## Targeted Insights
- Which features most strongly relate to defaults?  
- Are there high-risk patterns in previous loan refusals or cancellations?  
- Do certain demographic groups or employment types tend to default more?  
- What combination of attributes are present in most defaulters?

## Outcome
This EDA will help the loan company:
- Design better credit scoring models
- Define rules for automatic loan approvals/refusals
- Minimize financial risks while maximizing client coverage

## Deliverables
- Cleaned datasets  
- EDA notebooks with visuals and insights  
- Summary of findings and recommendations for business  

---


3. 'columns_description.csv' is data dictionary which describes the meaning of the variables.
