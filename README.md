# **Heart Failure Analysis and Predictive Modeling**

## **Team Members**
- Ahfaz Abdul  
- Sai Sushama Nimmagadda  
- Harish Babu Ramnieni  

## **Project Summary**
This project explores the Heart Failure Clinical Records Dataset to identify critical predictors of heart failure, analyze trends, and cluster patients for better management. The dataset comprises 299 patients and 13 features, including age, serum creatinine, ejection fraction, smoking, and diabetes. The project involved extensive data preprocessing, exploratory data analysis (EDA), regression modeling, and clustering to uncover patterns and insights.

**Key findings:**
- Serum creatinine, ejection fraction, and follow-up time are the most critical predictors of heart failure outcomes.  
- Clustering revealed distinct patient groups through KMeans and highlighted outliers using DBSCAN.  
- EDA showed age as a significant factor, with smoking and diabetes playing secondary roles.  

## **Methods**

## **Data Preprocessing**

- Handled missing and negative values to ensure data integrity.  
  **Analysis:** Replaced invalid negative values and missing values with median and forward/backward filling techniques, creating a clean dataset for analysis.  

- Scaled features using StandardScaler, MinMaxScaler, and Normalizer to ensure uniformity.  
  **Analysis:** Standardized features enabled effective clustering and regression performance across models.  

- Added derived features like a "Total" column for combined analysis.  
  **Analysis:** The "Total" column provided a consolidated measure of numeric feature contributions for enhanced insights.  

---

## **EDA and Visualization**

- Created scatter plots, heatmaps, histograms, and bar plots to understand data trends and relationships.  
  **Analysis:** 
  - Identified key trends such as the age distribution showing most patients in the 50–70 range.  
  - Heatmap revealed strong correlations between features like serum creatinine, ejection fraction, and heart failure outcomes.  

---

## **Regression Modeling**

- Used OLS, Lasso, Ridge, and ElasticNet regression to predict outcomes and identify key predictors.  
  **Analysis:** Serum creatinine, ejection fraction, and follow-up time emerged as the top predictors across all regression models, with ElasticNet providing a balanced regularization.  

---

## **Clustering Analysis**

- Applied KMeans, Agglomerative Clustering, and DBSCAN with PCA-reduced dimensions to identify patterns and outliers.  
  **Analysis:** 
  - KMeans grouped patients into distinct clusters, highlighting stratified risk profiles.  
  - DBSCAN detected outliers, providing insights into unique or atypical patient cases.  


## **Results**

- **Key Predictors:** Serum creatinine, ejection fraction, and time were identified as the most significant features influencing heart failure outcomes.  
- **Clustering Insights:** KMeans identified distinct patient groups, while DBSCAN detected unique and outlier cases.  
- **Visualization Insights:** Age showed a strong impact on outcomes, while smoking and diabetes had moderate effects.  

## **Why This Project?**
Heart failure is a major health issue globally, and predicting outcomes can save lives. This project aims to identify actionable insights and predictors that healthcare professionals can use to improve patient care and outcomes. By combining data analysis, regression modeling, and clustering, the project offers a multifactorial approach to understanding heart failure risk factors.

