# Inferential-Analysis-of-Academic-Labor-Costs-and-Student-Attendance-Expenditures

This project investigates whether a statistical relationship exists between the average salary of faculty members and the total cost of attendance at various higher education institutions. The study utilizes linear regression modeling to determine if higher tuition and fees translate into higher pay for professors.  

# Project Overview
The core research question of this study is: "Is there a relationship between average faculty salary and the cost of attendance?". Using a dataset of various colleges and universities, the project evaluates the predictive power of institution costs on academic compensation.  

# Dataset
The analysis uses the college.rds dataset. Key variables include:  


Average Faculty Salary: The response variable representing the monthly salary of faculty members.  


Cost of Attendance: The explanatory variable representing the total cost for a student to attend the institution.  

# Methodology
The study follows a rigorous statistical workflow using the R programming language:  


Exploratory Data Analysis (EDA): Visualizing the distribution of faculty salaries and attendance costs using histograms to check for symmetry and normality.  


Linear Regression Modeling: Building a model to quantify the correlation between the two primary variables.  

Assumption Testing:


Residuals vs. Predicted Plots: Used to confirm constant variability.  


Q-Q Plots: Used to verify that residuals are approximately normally distributed.  


Observed vs. Predicted Plots: Used to check the validity of the linear model.  

# Results & Findings

Weak Correlation: The analysis found a very weak correlation between what students pay and what professors are paid.  


Low Predictive Power: The R-squared value of approximately 0.138 indicates that only about 13.8% of the variance in faculty salaries can be explained by the cost of attendance.  


Conclusion: The study concludes that cost of attendance is not a good predictor of faculty salary. Even if tuition rises significantly, there is little statistical evidence to suggest a corresponding increase in professor pay within this dataset.  

# Technologies Used

Language: R   

Libraries:


tidyverse (for data manipulation and visualization)   


modelr and broom (for modeling and analysis)   


infer (for statistical inference)
