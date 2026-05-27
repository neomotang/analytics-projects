# Predicting loan pay-back

---

## Overview
In this project, a customer's likelihood to pay back a loan was predicted, using data from the November 2025 Kaggle playground series competition (https://www.kaggle.com/competitions/playground-series-s5e11/overview). A copy of the `Jupyter` notebook summarizing the model and its performance is provided (K_5_11_Loan.ipynb).

## Steps performed
- Visualise data to note distributions and outliers (`Seaborn` library)
- Explore feature selection and reduction using feature agglomeration and principal component analysis (`sklearn` library)
- Segment customers into clusters and visualize differences in attributes across the clusters (`Seaborn` & `sklearn`)
- Use pipelines to construct a predictive model that incorporates principal component analysis and customer segmentation (`sklearn` & `xgboost`):
  <img width="1818" height="941" alt="image" src="https://github.com/user-attachments/assets/c49d5451-1a32-4ee4-a359-b2b2f15aa8b5" />

- Validate the model on a hold-out dataset:
  <img width="588" height="448" alt="image" src="https://github.com/user-attachments/assets/75f95892-2cce-4d29-a47a-73d8c551ab9c" />


## Key insights
- Customers who are unemployed or students are more likely to not pay back their loans
- Attritubes of customers clusters with the highest average loans paid back:
-  - High **credit_score**, low **interest_rate** and good credit **grade_subgrade**(Cluster 5; 93%)
   - Low **annual_income** and low **debt_to_income_ratio** (Cluster 6; 91%)
- Attributes of customer clusters with the lowest average loans paid back:
- - Low **credit_score**, high **interest_rate** and poor credit **grade_subgrade** (Cluster 0; 66%)
  - Low **annual_income**, high **debt_to_income_ratio** and high **loan_amount** (Cluster 3; 68%)
