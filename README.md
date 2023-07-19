# About the hackathon

CarIns is a startup that provides insurance for cars. It is one of the best car insurance brands known for the highest claim settlement ratio. It was launched back in Oct 2020 and acquired its initial policyholders by providing a hassle-free claim process, instant policy issuance, and claim settlements at minimum coverages.


As it's a fast growing startup, the company would like to optimize the cost of the insurance by identifying the policyholders who are more likely to claim in the next 6 months. 

Now the company would like to use Data Science to identify the policyholders whose chances of filing a claim are high in the next 6 months. The company challenges the Data Science community to build a high-performance algorithm to predict if the policyholder will file a claim in the next 6 months or not based on the set of car and policy features.

# Insurance Claim Prediction Project

This repository contains the code and data for the Insurance Claim Prediction project. The goal of this project is to predict insurance claim outcomes using machine learning algorithms. The dataset used in this project contains 60,000 data points and 44 features.

## Steps Performed in the Project

1. **Load the Dataset**

   The dataset was loaded into the project for further analysis and modeling.

2. **Exploratory Data Analysis (EDA)**

   - Checked the shape of the dataset (60,000 data points) and examined the data types of different features.
   - Looked for missing values and duplicate values, but none were found in the dataset.
   - Performed univariate analysis and examined the distribution of various features.
      - Identified that some continuous features are categorized incorrectly, such as gear_box and number of cylinders.
      - Detected outliers in some of the continuous features.
   - Conducted bivariate analysis by plotting the distribution of various features against the target classes.
   - Identified class imbalance in the dataset.

3. **Feature Engineering**

   Generated additional features like force and rotational speed from the torque to enrich the dataset.

4. **Encoding**

   - Employed one-hot encoding for categorical features.
   - Utilized ordinal encoding for specific categorical features.
   - Standardized the numerical features.

5. **Handling Imbalanced Data**

   Used the Synthetic Minority Over-sampling Technique (SMOTE) to balance the highly imbalanced dataset.

6. **Handling Collinearity**

   Detected collinearity among various features in the dataset.
   Employed Recursive Feature Elimination (RFE) to remove multicollinearity.

7. **Modeling**

   - Split the dataset into a training set and a test set.
   - Applied various machine learning algorithms to the data.
   - Identified XGBoost as the best-performing algorithm with f1 scorre of 82%.
   - Used F1 score as the performance metric to evaluate the models.
       
