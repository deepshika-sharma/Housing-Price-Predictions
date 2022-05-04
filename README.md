# Project 2: Ames Housing Data and Kaggle Challenge

### Problem Statement
Identifying features helpful in predicting housing prices and using a model to gie us the best RSME score

### Executive Summary
This projects aims to use a regression model to predict housing prices for housing data from Ames. 

The Kaggle challenge provides us with a train dataset which has about 2000 observations and 80 features to train our model with and a test dataset to use for validation.

The Kaggle competiton takes the predictions and runs it against the test set and measures the Root Mean Squared Error.

Models used in this project are LinearRegression, Lasso and Ridge. Figuring out the features which can help increase property sales can help real estate agents as well as home owners looking to sell their property as it will give them an idea of what prices their prooperties could fetch or how they can improve their property's value.

### Data
|Feature|Description|
|-------|-----------|
|SalePrice|The property's sale price in dollars|
|MSSubClass|The building class|
|MSZoning|Identifies the general zoning classification of the sale|
|LotFrontage|Linear feet of street connected to property|
|LotArea|Lot size in square feet|
|Street|Type of road access to property|
|Alley|Type of alley access to property|
|LotShape|General shape of property|
|LandContour|Flatness of the property|
|Utilities|Type of utilities available|
|LotConfig|Lot configuration|
|FR2|Frontage on 2 sides of property|
|FR3|Frontage on 3 sides of property|
|LandSlope|Slope of property|
|Neighborhood|Physical location within Ames city limits|
|Condition1|Proximity to main road or railroad|
|Condition2|Proximity to main road or railroad (if a second is present)|
|BldgType|Type of dwelling|
|OverallQual|Overall material and finish quality|
|OverallCond|Overall condition rating|
|YearBuilt|Original construction date|
|YearRemodAdd|Remodel date (same as construction date if no remodeling or additions)|
|RoofStyle|Type of roof|
|Exterior1st|Exterior covering on house|
|Exterior2nd|Exterior covering on house (if more than one material)|
|MasVnrArea|Masonry veneer area in square feet|
|ExterQual|Exterior material quality|
|ExterCond|Present condition of the material on the exterior|
|BsmtQual|Height of the basement|
|BsmtCond|General condition of the basement|
|BsmtExposure|Walkout or garden level basement walls|
|BsmtFinType1|Quality of basement finished area|
|BsmtFinSF1|Type 1 finished square feet|
|BsmtFinType2|Quality of second finished area (if present)|
|BsmtFinSF2|Type 2 finished square feet|
|BsmtUnfSF|Unfinished square feet of basement area|
|TotalBsmtSF|Total square feet of basement area|
|Heating|Type of heating|
|HeatingQC|Heating quality and condition|
|CentralAir|Central air conditioning|
|Electrical|Electrical system|
|1stFlrSF|First Floor square feet|
|2ndFlrSF|Second floor square feet|
|LowQualFinSF|Low quality finished square feet (all floors)|
|GrLivArea|Above grade (ground) living area square feet|
|BsmtFullBath|Basement full bathrooms|
|BsmtHalfBath|Basement half bathrooms|
|FullBath|Full bathrooms above grade|
|HalfBath|Half baths above grade|
|Bedroom|Number of bedrooms above basement level|
|Kitchen|Number of kitchens|
|KitchenQual|Kitchen quality|
|TotRmsAbvGrd|Total rooms above grade (does not include bathrooms)|
|Functional|Home functionality rating|
|Fireplaces|Number of fireplaces|
|FireplaceQu|Fireplace quality|
|GarageType|Garage location 2Types More than one type of garage|
|GarageYrBlt|Year garage was built|
|GarageFinish|Interior finish of the garage Fin Finished RFn Rough Finished Unf Unfinished NA No Garage|
|GarageCars|Size of garage in car capacity|
|GarageArea|Size of garage in square feet|
|GarageQual|Garage quality|
|GarageCond|Garage condition|
|PavedDrive|Paved driveway|
|WoodDeckSF|Wood deck area in square feet|
|OpenPorchSF|Open porch area in square feet|
|EnclosedPorch|Enclosed porch area in square feet|
|3SsnPorch|Three season porch area in square feet|
|ScreenPorch|Screen porch area in square feet|
|PoolArea|Pool area in square feet|
|PoolQC|Pool quality|
|Fence|Fence quality|
|MiscFeature|Miscellaneous fetaure not covered in other categories|
|MiscVal: $Value of miscellaneous feature|
|MoSold|Month Sold|
|YrSold|Year Sold|
|SaleType|Type of sale|

### Conclusion and Recommendations
Features with the strongest coefficients:
* gr_liv_area
* kitchen_qual
* garage_cars
* overall_qual
* neighborhood_stonebr
* neighborhood_nridght
* mas_vnr_area

Some of the things homeowners/property investors could improve to increase the value of the houses is:
* Improve the kitchen quality
* Improve the overall condition of the house
* Look for houses to sell in neighborhoods like Stonebrook and Northridge

