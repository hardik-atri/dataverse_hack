# About the hackathon

CarIns is a startup that provides insurance for cars. It is one of the best car insurance brands known for the highest claim settlement ratio. It was launched back in Oct 2020 and acquired its initial policyholders by providing a hassle-free claim process, instant policy issuance, and claim settlements at minimum coverages.


As it's a fast growing startup, the company would like to optimize the cost of the insurance by identifying the policyholders who are more likely to claim in the next 6 months. 

Now the company would like to use Data Science to identify the policyholders whose chances of filing a claim are high in the next 6 months. The company challenges the Data Science community to build a high-performance algorithm to predict if the policyholder will file a claim in the next 6 months or not based on the set of car and policy features.

# Approach
Started with Exploratory Data Analysis.  

       * Data is imbalanced.
       * Data visualization.
       * Categorize features as binary , ordinal , one_hot, numerical.
       
Did some Feature Engineering / Feature Selection  

       * Used VIF to check for multicollinearity and removed using RFE.
       * Used SMOTE to balance the dataset

Modelling  

       * Applied different models and XGBoost stands out with 82 % f1 score.
       
