# Liver Health Data Analysis  

---

## Project Overview  

This project analyzes a liver health dataset containing clinical and laboratory data to classify patients as liver disease positive or negative. The dataset supports epidemiological insights and medical diagnosis models. Key objectives include:

- Classification of liver disease presence  
- Exploratory data analysis (EDA) to understand feature associations  
- Feature impact analysis on diagnosis  
- Application of data mining and machine learning techniques  

---

## Technologies Used  

- Python (pandas, matplotlib, seaborn, scikit-learn)  
- Data mining and machine learning libraries

---

## Dataset Details  

- Multivariate dataset with numerical and categorical features related to liver function (enzymes, bilirubin, protein ratios)  
- Reflects real-world clinical data for educational and diagnostic use  

---

## Data Preprocessing  

- Handled missing values (e.g., Albumin_and_Globulin_Ratio) via imputation  
- Verified no duplicated rows present  
- Cleaned column names for consistency  
- Encoded categorical variables for model compatibility  
- Standardized numerical features for better model performance  

---

## Exploratory Data Analysis & Visualization  

- Generated statistical summaries (mean, median, standard deviation) for numeric attributes  
- Created boxplots and scatterplots for outlier detection and visualization  
- Visualized categorical attributes with count plots  
- Produced correlation heatmaps and matrices to explore feature relationships  

---

## Outlier Handling  

- Identified outliers in key features such as Total_Bilirubin and enzyme levels  
- Applied Interquartile Range (IQR) method to remove extreme outliers  
- Compared dataset before and after outlier removal with scatter plots  

---

## Model Performance & Comparison  

- Evaluated Logistic Regression, Decision Tree, and Random Forest models  
- Random Forest achieved highest accuracy (78.95%), best recall (0.89), and precision (0.84)  
- Logistic Regression had high recall (0.87) but lower overall accuracy (71.05%)  
- Decision Tree showed the lowest recall and accuracy (69.30%)  
- Random Forest preferred due to balanced precision and recall, minimizing false negatives critical for medical diagnosis  

---

## Conclusion  

The Random Forest model provides the most reliable predictions for liver disease classification, balancing sensitivity and specificity which is vital in medical applications. This project demonstrates effective data preprocessing, visualization, and machine learning techniques applied to real clinical data.






