# Jamboree Education_Linear Regression
Jamboree has helped thousands of students like you make it to top colleges abroad. Be it GMAT, GRE or SAT, their unique problem-solving methods ensure maximum scores with minimum effort.They recently launched a feature where students/learners can come to their website and check their probability of getting into the IVY league college. This feature estimates the chances of graduate admission from an Indian perspective.

## Bisinuss problem
 Understanding what factors are important in graduate admissions and how these factors are interrelated among themselves. It will also help predict one's chances of admission given the rest of the variables.

## Column Profiling:
    •	Serial No. (Unique row ID)
    •	GRE Scores (out of 340)
    •	TOEFL Scores (out of 120)
    •	University Rating (out of 5)
    •	Statement of Purpose and Letter of Recommendation Strength (out of 5)
    •	Undergraduate GPA (out of 10)
    •	Research Experience (either 0 or 1)
    •	Chance of Admit (ranging from 0 to 1)
    

## Project Accomplishments and Process Overview
     •	Import the dataset and do usual exploratory data analysis steps like checking the structure & characteristics of the dataset.
     •	Drop the unique row Identifier if you see any. This step is important as you don’t want your model to build some understanding based on row numbers.
     •	Using Non-graphical and graphical analysis for getting inferences about variables.
         o	This can be done by checking the distribution of variables of graduate applicants.
     •	Once you’ve ensured that students with varied merit apply for the university, you can start understanding the relationship between different factors responsible for graduate admissions.
     •	Check correlation among independent variables and how they interact with each other.
     •	Use Linear Regression from (Statsmodel library) and explain the results.
     •	Test the assumptions of linear regression:
         o	Multicollinearity check by VIF score
         o	Mean of residuals
         o	Linearity of variables (no pattern in residual plot)
         o	Test for Homoscedasticity
         o	Normality of residuals
     •	Do model evaluation- MAE, RMSE, R2 score, Adjusted R2.
     •	Provide actionable Insights & Recommendations
     •	Try out different Linear Regressions

## Concept Used:
    •	Exploratory Data Analysis
    •	Linear Regression
