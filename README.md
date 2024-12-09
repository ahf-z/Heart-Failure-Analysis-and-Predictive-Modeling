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

### **Data Preprocessing**
- Handled missing and negative values.  
- Scaled features using StandardScaler, MinMaxScaler, and Normalizer.  
- Added derived features like a "Total" column for combined analysis.  

### **EDA and Visualization**
- Created scatter plots, heatmaps, histograms, and bar plots to understand data trends and relationships.  

### **Regression Modeling**
- Used OLS, Lasso, Ridge, and ElasticNet regression to predict outcomes and identify key predictors.  

### **Clustering Analysis**
- Applied KMeans, Agglomerative Clustering, and DBSCAN with PCA-reduced dimensions to identify patterns and outliers.  

## **Results**

- **Key Predictors:** Serum creatinine, ejection fraction, and time were identified as the most significant features influencing heart failure outcomes.  
- **Clustering Insights:** KMeans identified distinct patient groups, while DBSCAN detected unique and outlier cases.  
- **Visualization Insights:** Age showed a strong impact on outcomes, while smoking and diabetes had moderate effects.  

## **Why This Project?**
Heart failure is a major health issue globally, and predicting outcomes can save lives. This project aims to identify actionable insights and predictors that healthcare professionals can use to improve patient care and outcomes. By combining data analysis, regression modeling, and clustering, the project offers a multifactorial approach to understanding heart failure risk factors.

