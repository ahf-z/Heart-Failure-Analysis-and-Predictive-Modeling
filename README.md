# Heart Failure Analysis and Predictive Modeling

**Authors**: Sai Sushama Nimmagadda, Ahfaz Abdul, Harish Babu Ramineni  
**Course**: CS 6010 | Data Science Programming  
**Professor**: Dr. Robert Green  
**Due Date**: December 09, 2024

## Project Summary

This project explores the **Heart Failure Clinical Records Dataset** to identify critical predictors of heart failure, analyze trends, and cluster patients for better management. The dataset comprises 299 patients and 13 features, including age, serum creatinine, ejection fraction, smoking, and diabetes. The project involved extensive data preprocessing, exploratory data analysis (EDA), regression modeling, and clustering to uncover patterns and insights.

### Key Findings:

- **Serum creatinine**, **ejection fraction**, and **follow-up time** are the most critical predictors of heart failure outcomes.
- **Clustering** revealed distinct patient groups through **KMeans** and highlighted outliers using **DBSCAN**.
- **EDA** showed age as a significant factor, with smoking and diabetes playing secondary roles.

---

## Methods

### Clustering Analysis

- Applied **KMeans**, **Agglomerative Clustering**, and **DBSCAN** (after reducing dimensions with PCA) to identify patient patterns and detect outliers.
- **Key Findings**:
  - **KMeans** identified distinct clusters of patients, showing stratified risk profiles and helping us understand subgroups based on various clinical factors.
  - **DBSCAN** helped detect outliers, providing valuable insights into unique or atypical patient cases that might require special attention.
  - **Agglomerative Clustering** did not provide much useful information in this context, as the clusters formed were not as distinct or interpretable as those found with **KMeans**.

---

### Regression Modeling

- Used **OLS**, **Lasso**, **Ridge**, and **ElasticNet** regression techniques to predict outcomes and identify important predictors.
- **Key Findings**:
  - **Serum creatinine**, **ejection fraction**, and **follow-up time** emerged as the most important predictors across all regression models.
  - **ElasticNet** was found to provide a balanced regularization approach, handling both feature selection and shrinkage effectively.
  - **Linear regression** Linear Regression outperformed the other models with the lowest RMSE, indicating it best captures the dataset's relationships without needing regularization.

---

### EDA and Visualization

- Created **four main visualizations** to understand data trends and feature relationships.

#### 1. **Age Distribution**:

- The **histogram** showed that most patients were between **50-70 years old**, indicating that heart failure primarily affects middle-aged and older adults. This highlights the importance of early detection and intervention in this age group.

#### 2. **Serum Creatinine vs. Ejection Fraction**:

- The **scatter plot** showed a negative correlation between **serum creatinine** and **ejection fraction**, indicating that higher creatinine levels, which reflect kidney dysfunction, are associated with lower heart function. This suggests that monitoring kidney health may be critical in assessing heart failure risk.

#### 3. **Follow-up Time vs. Death Event**:

- The **bar plot** illustrated that patients with longer follow-up times had higher mortality rates, underscoring the significance of continuous monitoring for heart failure patients. Longer follow-up may also indicate more severe cases of heart failure.

#### 4. **Smoking and Diabetes**:

- The **heatmap** revealed that **smoking** and **diabetes** had a moderate correlation with heart failure outcomes. Although not as strong as the effects of **serum creatinine** or **ejection fraction**, these factors still play a role in heart failure prognosis, highlighting the importance of lifestyle and metabolic health in managing the condition.

---

### Final Notebook Overview:

A final notebook has been created to give a comprehensive overview of all the analyses conducted throughout the project in the presentation folder. This notebook provides a summary of each notebook used in the project, allowing for a structured walkthrough of the data preprocessing, EDA, regression modeling, and clustering processes. It serves as a consolidated reference for understanding the overall analysis and results.

The remaining four notebooks were created for extra analysis, trial and error, and experimentation with different approaches. These notebooks explore various aspects of the project for in-depth and detailed exploration, offering alternative methods and insights before finalizing the analysis in the final notebook.

---

## Results

### Key Predictors:

- **Serum creatinine**, **ejection fraction**, and **follow-up time** were identified as the most significant predictors of heart failure outcomes.

### Clustering Insights:

- **KMeans** clustering revealed different patient groups with distinct heart failure risks.
- **DBSCAN** detected outliers that might indicate unique cases or conditions not typically seen in other patients.
- **Agglomerative Clustering** did not reveal any useful clustering patterns for this dataset.

### Visualization Insights:

- **Age** had a significant impact on outcomes, with older patients at a higher risk of death due to heart failure.
- **Serum creatinine** and **ejection fraction** had a stronger relationship with heart failure outcomes than other factors.
- **Smoking** and **diabetes** showed a moderate correlation with mortality, suggesting they are secondary but still important contributors to heart failure risk.

---

## Why This Project?

Heart failure is a major health issue globally, and predicting outcomes can save lives. This project aims to identify actionable insights and predictors that healthcare professionals can use to improve patient care and outcomes. By combining data analysis, regression modeling, and clustering, the project offers a multifactorial approach to understanding heart failure risk factors.
