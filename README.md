# House-Price-Prediction
Build a machine learning model that will give the best future sales prediction of homes

# Data Description

There are two datasets available –
• train_2016 – This dataset consists of the target variable i.e. the logerror
• properties_2016 – Contents all the features related to the property/home.

There are around 60 attributes in the dataset on basis of which the model can be built.
Some of the important features amongst them are as follows:
• train_2016:
1. parcelid - Unique identification for every parcel
2. transactiondate - The date on which the home was sold
3. logerror - The residual between the actual and the predicted sale price of homes.
(Target Array)
• properties_2016:
1. parcelid - Unique identification for every parcel (common in both the datasets)
2. bathroomcnt - Total number of bathrooms in the house
3. bedroomcnt - Total number of bedrooms in the house
4. buildingqualitytypeid - This gives the quality assessment of the building ranging from
best to worst.
5. finishedsqaurefeet12 - Finished living area of the house.
6. fips - This stand for Federal Information Processing Standard code (for more detail
regarding this check: https://en.wikipedia.org/wiki/FIPS_county_code
7. latitude & longitude - longitude and latitude of the home location
8. propertylandusetypeid - This gives the type of land the property is zoned for.
9. regionidcity - The city in which the property is situated.
10. regionidcounty - The county where the property is situated.
11. regionidzip - This provides the zip code for the location of the property.
12. taxamount - Property tax for each assessment year

# Tech Stack:

➢ Language - Python
➢ Libraries - Scikit-learn, pandas, numpy, matplotlib, seaborn, scipy, xgboost, joblib


