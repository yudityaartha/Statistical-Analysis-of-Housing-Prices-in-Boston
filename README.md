# Statistical Analysis of Housing Prices in Boston

This project explores the **Boston Housing Prices** dataset using Python. 

The goal is to uncover key factors influencing house prices and apply **exploratory data analysis (EDA)** and **hypothesis testing** to draw meaningful conclusions.

---

## Project Objectives
In this project I need to uncover key insights, discover relations between multiple factors and draw correct conclusion from the boston housing prices dataset.
This project is one of peer graded assignment from IBM Data Analyst Certification from Coursera


I need to answer these followings and implementing my hypothesis testing skills on this task:

### TASK 1
- Question 1 : Is there a significant difference in median value of houses bounded by the Charles river or not? (T-test for independent samples)
- Question 2 : Is there a difference in Median values of houses (MEDV) for each proportion of owner occupied units built prior to 1940 (AGE)? (ANOVA)
- Question 3 : Can we conclude that there is no relationship between Nitric oxide concentrations and proportion of non-retail business acres per town? (Pearson Correlation)
- Question 4 : What is the impact of an additional weighted distance  to the five Boston employment centres on the median value of owner occupied homes? (Regression analysis)

### TASK 2
- Question 1 : For the "Median value of owner-occupied homes" provide a boxplot
- Question 2 : Provide a  bar plot for the Charles river variable
- Question 3 : Provide a boxplot for the MEDV variable vs the AGE variable. (Discretize the age variable into three groups of 35 years and younger, between 35 and 70 years and 70 years and older)
- Question 4 : Provide a scatter plot to show the relationship between Nitric oxide concentrations and the proportion of non-retail business acres per town. What can you say about the relationship?
- Question 5 : Create a histogram for the pupil to teacher ratio variable

These questions will train my skill to do followings:
- Perform **exploratory data analysis** and **descriptive statistical analysis** of the dataset
- Create required data viz to help EDA and statistical analysis process and to have better understanding of the dataset
- Find relationship significance between multiple variables
- Interpret coefficients to understand real-world implications

---

## Skills Applied

- **Python (Pandas, NumPy)** for data wrangling & analysis  
- **Seaborn & Matplotlib** for data visualization  
- **Scipy and Statsmodels** for hypothesis testing
- **Feature engineering & correlation analysis**  

---

## Dataset

- Dataset used: 'https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-ST0151EN-SkillsNetwork/labs/boston_housing.csv'
- Target variable: **MEDV** (Median value of owner-occupied homes in $1000s)
- Variables include crime rate, proportion of non-retail business acres, nitric oxide concentration, average number of rooms, etc.

---

## Key Insights

#### A. There is a statistical significant difference (or correlation) on:
- Nitric oxide concentrations and proportion of non-retail business acres per town 
- Weighted distance to the five Boston employment centres on the median value of owner occupied homes 
- Median value of houses that bounded by and not bounded by the Charles river 
- Residual analysis shows the model's limitations and non-linear patterns

#### B. There are some outliers for MEDV value (showed on boxplot), the median values lies around $21.000

#### C. Total of Charles River dummy variable that tract doest not bounds river is significantly higher than not bounded by river

#### D. It is indicated that owner age that occupied houses which age lower than 35 shows relatively higher median value than other group age (from the boxplot chart)
Also MEDV of 35 - 70 age group shows more frequent outliers compare to other groups

---

## Notebooks & Code

You can explore the full Jupyter notebook here:  
🔗 [Housing_Prices_in_Boston.ipynb](https://github.com/yudityaartha/Statistical-Analysis-of-Housing-Prices-in-Boston/blob/main/Housing_Prices_in_Boston.ipynb)

---

## Future Improvements

- Try **log transformation** or **polynomial features** to improve model performance
- Use **Ridge/Lasso Regression** to handle multicollinearity
- Apply **feature selection** or **PCA** for dimensionality reduction
- Test with modern housing datasets like **Ames Housing**

---

## About Me

I’m Yuditya Artha — a licensed apothecary pivoting into data science and analytics.  
This project is part of my portfolio to demonstrate practical skills in data cleaning, analysis, and modeling using Python.

Let's connect on [LinkedIn](https://www.linkedin.com/in/yuditya-artha/) 👋

---

## Feedback or Collaboration?

Open to suggestions, collaboration, or feedback!  
Feel free to raise an issue or DM me on [GitHub](https://github.com/yudityaartha) or [LinkedIn](https://www.linkedin.com/in/yuditya-artha/).

