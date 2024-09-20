# Description  
Evanston Hospital is a comprehensive acute-care facility in Illinois, US. The hospital offers a wide range of services and surgical specialities, in addition to having high-end lab capabilities. Despite spending a considerable amount of resources on improving its services, the hospital’s CMS rating has remained at 3 for the past 5 years, and this has led to a steady decline in revenue for the hospital. For hospitals like Evanston, these ratings directly influence the choice made by consumers who are looking for a healthcare provider and would, therefore, have a significant impact on the hospitals’ revenues. As a consulting company hired by Evanston, our task is to identify possible root causes for the hospital getting such an average rating and recommend measures to mitigate this problem.
# Objective
1. To build a rating prediction model and determine the factors that are impacting the rating.
2. To predict the Evanston hospital rating using the model and recommend the measures they need to concentrate on to improve the hospital rating.

# Steps Taken
1. Understanding the data, cleaning it, and preparing it for further analysis
2. Performing univariate/bivariate analysis and feature engineering
3. Missing Value treatment
4. Outlier and Skewness treatment
5. Training different machine learning models on the data Choosing
6. Evaluating the model that provides the best metrics
7. Data storytelling using the insights and modelling results, and proposing a business solution
   
# Metrics Used
Accuracy, Precision, Recall, AUC score, Classification report

# Models Used: 
1. Logistic Regression
2. Logistic Regression with Smote Sampling
3. Random Forest
4. Gradient boost with RFE
5. Gradient boost with RFE with Smote

# Model Evaluation 
Gradient Boost after Smote Samling with RFE is chosen as the best model for this use case.

<img width="230" alt="image" src="https://github.com/user-attachments/assets/5ffc890e-4550-4637-a27b-70e15a33bf22">

# Feature Importance 
Readmission and Mortality scores are directly impacting the star rating. Below given are the impacting measures
<img width="232" alt="image" src="https://github.com/user-attachments/assets/6ed93797-a5a0-4a9c-b987-58f303d3fddb">

Below are the Top factors The hospital needs to focus on to improve their reatings.
![image](https://github.com/user-attachments/assets/6ca31eff-a87e-406c-b7de-99472abc0ccc)
