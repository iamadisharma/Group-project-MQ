# Relation between Firearm Background checks and Gun related deaths in USA


# Group - 1



## Overview
We are going to perform the analysis on NICS-firearm-background-checks dataset which is in CSV format,  it provides background information on the person buying firearms Mandated by the Brady Handgun Violence Prevention Act of 1993 and launched by the FBI on November 30, 1998, NICS is used by Federal Firearms Licensees (FFLs) to instantly determine whether a prospective buyer is eligible to buy firearms or explosives. Before ringing up the sale, cashiers call in a check with the FBI or other designated agencies to ensure that each customer does not have a criminal record or isn’t otherwise ineligible to make a purchase. We are going to analyse the customer behaviour trends as well check if there is any relationship bewtween Firearm Background checks and Gun related deaths in USA. The databases which are used for this analysis is listed as follows with their source:

### Source 1: https://github.com/BuzzFeedNews/nics-firearm-background-checks
•	FBI NICS Firearm Background Check Data.

### Source 2: https://web.archive.org/web/20180829040259/https://docs.google.com/spreadsheets/d/e/2PACX-1vSSw6_GoTEqxIiLYTPs8_AmJ1P4DnpEJJYyVw0yAauGOPR72_Rm2RFIZwhgvt3wQQa51hhfMobByRSy/pubhtml
•	Second Dataset for Gun-related deaths by age and sex 1999-2016 in USA.


### Source 3 : https://data.world/awram/us-mass-shootings
•	Third Dataset for Gun-related mass shootings in USA from 1982 to 2019.

### Source 4 : https://data.world/azel/gun-deaths-in-america
•	Fourth Dataset for Gun-related deaths in USA from 2012 to 2014 **This Data is Extra and we may or may not use this**


## Goals
Analysing the customer behaviour trends of fire arm purchases in different metropolitan cities in the United States of America. We are going perform our behaviour analysis on first data from 1998-2021 and then perform analysis on the second data which is gun deaths from 2012-2014. 
  1. We are going to analyse if the Firearms have had or has any impact or have an influence on gun crime in the USA.
  2. We are going to analyse if there is any relation between the most background checks done and crime rate in a particular state.
  3. We are going to analyse which age group people have succumbed to gun crime.
  4. We are going to Predict the numbers of checks in the near future by various techniques. 
  


### Format
The data is in csv files format.



### Working on Data
Data Cleaning: 
  1. Dropping the years which are not relavent to the analysis. The data for the year 2021 does not have all months data becuase it is still      April 2021 while we start the project. So we will not be using the data for 2021 across all the datasets. 
  2. Filling in missing values if there are any.



### Techniques 
Use of Machine Learning Techniques like- Linear or logistic regression and polynomial regression and K-mean clustering.
1.	For evaluation- Mean Square Error, Accuracy score, Mean Absolute Error, F-score are expected to be used.
2.	For parameter analysis- hyper parameters like Train, Test Split Estimator and KNN Classifier or Logistic Regression Classifier will be used.
3.	Cross Validation will be used for testing.



### Project Plan
•	Week 8-9: Data Cleaning
•	Week 10: Creating different Models using algorithms and testing.
•	Week 12: Preparation of Report and Video Presentation.








