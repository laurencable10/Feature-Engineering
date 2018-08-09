# Feature Engineering 
## Using Heads of State Data 
* This notebook uses regression techniques to predict the length of a ruler's reign, implementing engineered features with Pandas to build Linear Regression Models with the Stats Models library,

* The dataset utilized contains rulers' names, the length of reign, the age term began, and rulers' religious, politcal, and royal statuses among other features. 

## Overview 

### Exploratory Data Analysis 
- Leveraging the .describe( ) method to produce notable findings and do necessary data clean-up/datatype conversion  
- Subsetting DataFrame to include only those rulers who are not currently heads of state 
- Converting target data to expressing length of reign in terms of years 

### Investigating Potential Relationships 
- Whether being royal has a significant effect on the length of one's reign
  - Creating royal dummy variable 
  - Building OLS model and interpreting model coefficient to determine relationship
- Whether having a religion listed has a significant effect on the length of one's reign
  - Creating religion dummy variable 
  - Building OLS model and interpreting model coefficient to determine relationship 

### Model Building 
- Defining X and y variables 
- Building MLR model using proper format for Stats Models (y,X) and creating constant
- Accessing and interpreting model coefficients/constant using .summary( ) method 
