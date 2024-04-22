# House Prices - Advanced Regression Techniques
![image](https://github.com/nayana142/Regression_Case_Studies/assets/120770261/e6b30b2b-b25e-4f91-93c5-36d0e80b67d8)![image](https://github.com/nayana142/Regression_Case_Studies/assets/120770261/6f729d17-c422-4907-826f-a4a52a84c697)
## Business Problem
     Predict the sales price for each house. For each Id in the test set, you must predict the value of the SalePrice variable. 
## File descriptions
    * train.csv - the training set
    * test.csv - the test set
    * data_description.txt - full description of each column, originally prepared by Dean De Cock but lightly edited to match the column names used here
    * sample_submission.csv - a benchmark submission from a linear regression on year and month of sale, lot square footage, and number of bedrooms
## Column Profiling:
    Data fields
    Here's a brief version of what you'll find in the data description file.
    
    SalePrice - the property's sale price in dollars. This is the target variable that you're trying to predict.
    MSSubClass: The building class
    MSZoning: The general zoning classification
    LotFrontage: Linear feet of street connected to property
    LotArea: Lot size in square feet
    Street: Type of road access
    Alley: Type of alley access
    LotShape: General shape of property
    LandContour: Flatness of the property
    Utilities: Type of utilities available
    LotConfig: Lot configuration
    LandSlope: Slope of property
    Neighborhood: Physical locations within Ames city limits
    Condition1: Proximity to main road or railroad
    Condition2: Proximity to main road or railroad (if a second is present)
    BldgType: Type of dwelling
    HouseStyle: Style of dwelling
    OverallQual: Overall material and finish quality
    OverallCond: Overall condition rating
    YearBuilt: Original construction date
    YearRemodAdd: Remodel date
    RoofStyle: Type of roof
    RoofMatl: Roof material
    Exterior1st: Exterior covering on house
    Exterior2nd: Exterior covering on house (if more than one material)
    MasVnrType: Masonry veneer type
    MasVnrArea: Masonry veneer area in square feet
    ExterQual: Exterior material quality
    ExterCond: Present condition of the material on the exterior
    Foundation: Type of foundation
    BsmtQual: Height of the basement
    BsmtCond: General condition of the basement
    BsmtExposure: Walkout or garden level basement walls
    BsmtFinType1: Quality of basement finished area
    BsmtFinSF1: Type 1 finished square feet
    BsmtFinType2: Quality of second finished area (if present)
    BsmtFinSF2: Type 2 finished square feet
    BsmtUnfSF: Unfinished square feet of basement area
    TotalBsmtSF: Total square feet of basement area
    Heating: Type of heating
    HeatingQC: Heating quality and condition
    CentralAir: Central air conditioning
    Electrical: Electrical system
    1stFlrSF: First Floor square feet
    2ndFlrSF: Second floor square feet
    LowQualFinSF: Low quality finished square feet (all floors)
    GrLivArea: Above grade (ground) living area square feet
    BsmtFullBath: Basement full bathrooms
    BsmtHalfBath: Basement half bathrooms
    FullBath: Full bathrooms above grade
    HalfBath: Half baths above grade
    Bedroom: Number of bedrooms above basement level
    Kitchen: Number of kitchens
    KitchenQual: Kitchen quality
    TotRmsAbvGrd: Total rooms above grade (does not include bathrooms)
    Functional: Home functionality rating
    Fireplaces: Number of fireplaces
    FireplaceQu: Fireplace quality
    GarageType: Garage location
    GarageYrBlt: Year garage was built
    GarageFinish: Interior finish of the garage
    GarageCars: Size of garage in car capacity
    GarageArea: Size of garage in square feet
    GarageQual: Garage quality
    GarageCond: Garage condition
    PavedDrive: Paved driveway
    WoodDeckSF: Wood deck area in square feet
    OpenPorchSF: Open porch area in square feet
    EnclosedPorch: Enclosed porch area in square feet
    3SsnPorch: Three season porch area in square feet
    ScreenPorch: Screen porch area in square feet
    PoolArea: Pool area in square feet
    PoolQC: Pool quality
    Fence: Fence quality
    MiscFeature: Miscellaneous feature not covered in other categories
    MiscVal: $Value of miscellaneous feature
    MoSold: Month Sold
    YrSold: Year Sold
    SaleType: Type of sale
    SaleCondition: Condition of sale



# Jamboree Education_Linear Regression
![image](https://github.com/nayana142/Regression_Case_Studies/assets/120770261/ec74b1e0-f795-47b8-a2b5-d664b5dcd106)

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
