
# AI Job Market Analysis & Salary Prediction

## Project Overview
This project, created by **Karan Zaveri** (karanzaveri92@gmail.com), provides an in-depth analysis of the AI job market and predicts salary trends using machine learning models. The dataset is sourced from **Kaggle** and contains comprehensive data on AI-related job roles, requirements, and salary information. The goal is to uncover trends, analyze key factors influencing salaries, and provide predictions based on those factors.

---

## Table of Contents
1. [Introduction](#introduction)
2. [Project Structure](#project-structure)
3. [Dataset Information](#dataset-information)
4. [Project Workflow](#project-workflow)
5. [Key Outcomes from Analysis](#key-outcomes-from-analysis)
6. [Visualizations](#visualizations)
7. [Modeling and Predictions](#modeling-and-predictions)
8. [Conclusion](#conclusion)
9. [Contact Information](#contact-information)

---

## Introduction
The AI job market is growing rapidly, and understanding salary trends based on factors such as location, experience, and job role can provide valuable insights for job seekers, companies, and policymakers. This project aims to:
- Analyze current job market trends in the AI field.
- Predict salaries based on job-specific attributes using machine learning models.

---

## Project Structure

The project follows a modular structure for easy navigation:
```

AI_Job_Market_Analysis_Salary_Prediction/ │ ├── data/ # Contains the dataset used for analysis ├── notebooks/ # Jupyter Notebooks with step-by-step analysis ├── models/ #Saved Models ├── visualizations/ # Images and plots generated during the analysis ├── [README.md](http://README.md) 

```

---

## Dataset Information
The dataset used in this project is derived from **Kaggle** and includes the following key features:
- **Job Titles**: Titles of AI-related positions.
- **Company Names**: Companies hiring for AI roles.
- **Location**: The geographical location of the job.
- **Experience Level**: Junior, mid-level, and senior-level AI roles.
- **Industry**: The sector in which the job belongs.
- **Salary**: Salaries in different currencies.
- **Company Size**: Small, medium, or large enterprises.

We normalized the salary data to ensure consistency across different currencies.

---

## Project Workflow

The workflow for this project can be divided into five key steps:

1. **Data Cleaning and Preprocessing**:
   - Cleaned missing or inconsistent data and normalized salaries.
   - Converted categorical features such as job titles, industries, and company sizes into numerical format for model training.

2. **Exploratory Data Analysis (EDA)**:
   - Performed in-depth analysis of job market trends.
   - Visualized the distribution of job roles, salaries, and experience levels across different industries and locations.

3. **Feature Engineering**:
   - Created new features such as "Experience Level" and "Company Size" that improved model performance.
   - Converted salary values into annual figures for accurate prediction.

4. **Modeling**:
   - Employed several machine learning models, including:
     - Linear Regression
     - Decision Trees
     - Random Forest
     - Gradient Boosting

5. **Evaluation and Prediction**:
   - Evaluated models using metrics such as Mean Absolute Error (MAE) and R-squared values.
   - Used the best-performing model to predict salaries for new AI-related job roles.

---

## Key Outcomes from Analysis

### 1. **Job Location vs. Salary**
   - Salaries for AI roles vary significantly based on geography.
   - **Key finding**: AI jobs in the US, Canada, and certain parts of Europe offer notably higher salaries compared to regions in Asia or South America.

### 2. **Experience Level Impact**
   - As expected, higher experience levels correlate with higher salaries.
   - **Key finding**: Senior AI professionals earn nearly 2-3 times more than entry-level positions in the same geographical location.

### 3. **Industry Trends**
   - Certain industries, like finance and tech, tend to offer higher salaries compared to others, such as education or healthcare.
   - **Key finding**: Tech companies are the highest-paying sector for AI roles, while education-related AI roles tend to offer lower compensation.

### 4. **Company Size and Salary**
   - Larger companies generally offer higher salaries.
   - **Key finding**: Companies with over 500 employees tend to pay 20-30% more compared to startups or small companies.

---

## Visualizations

### 1. **Salary Distribution by Location**
   - A **box plot** shows the distribution of salaries across different geographical regions. Countries like the **US** and **Canada** offer significantly higher salaries for AI jobs compared to regions like **India** or **Brazil**.
   - **Insight**: Salary ranges in developed countries have a wider spread, indicating more variability in the job market.

### 2. **Experience Level vs. Salary**
   - A **bar chart** illustrates the relationship between experience level and salary. As anticipated, higher experience levels lead to substantially higher salaries.
   - **Insight**: There's a sharp increase in salary after 5+ years of experience in the AI domain.

### 3. **Industry-wise Salary Comparison**
   - A **heatmap** was used to show how different industries compare in terms of salary. The **finance** and **tech** industries clearly stand out, offering premium compensation for AI expertise.
   - **Insight**: AI professionals working in **finance** earn the highest average salaries compared to other sectors.

### 4. **Company Size Impact on Salary**
   - A **scatter plot** of company size versus salary demonstrates a positive correlation, with larger companies offering more competitive pay packages.
   - **Insight**: Small firms, especially startups, tend to have a higher range of variance in salary, with some niche firms offering surprisingly high salaries for specialized roles.

---

## Modeling and Predictions

### Model Performance:
- After testing multiple models, the **Random Forest Regressor** was the best-performing model for salary prediction, with:
  - **Mean Absolute Error (MAE)**: 5,200 (indicative of average salary prediction error).
  - **R-squared value**: 0.82, which shows that the model can explain 82% of the salary variance based on job attributes.

### Key Features Affecting Salary:
- **Experience Level**: The most important predictor, where higher experience consistently led to higher salary.
- **Job Location**: Plays a significant role in predicting salary, with certain locations (like the US and Europe) offering notably higher salaries.
- **Industry**: The model highlighted industry as a key feature, with tech and finance sectors being the highest-paying.

### Prediction:
- The final Random Forest model can accurately predict salary ranges for AI jobs based on the key features such as job title, location, and experience level. The model provides an average salary prediction with a relatively low error margin.

---

## Conclusion

This project successfully analyzed the AI job market and provided useful predictions for salary trends. Key takeaways include:
- **Geographic location**, **experience level**, and **industry** play a critical role in determining AI job salaries.
- **Machine learning models** like Random Forest can effectively predict salary ranges based on job attributes.
- AI professionals in developed countries and large firms receive significantly higher salaries compared to their peers in smaller firms or less developed regions.

The predictive models built in this project can assist companies and job seekers alike by offering salary insights based on job-specific parameters.

---

## Contact Information

**Author**: Karan Zaveri  
**Email**: karanzaveri92@gmail.com  
**Project Dataset Source**: Kaggle  
