# Data Integration for property price prediction in Victoria

# Introduction

This repository is used for Data Integration from various external sources to prepare a final dataset with feature engineering that can be helpful in predicting the prices of properties in Victoria. 

It also involves reshaping on some variables and some understanding of modelling on those features that can be helpful in predicting the property prices in Victoria. For building a more robust model, more set of features should be used from the final dataset obtained.  

The dataset prepration uses only a sample of dataset. However, full dataset can be used for accurate performance.

# About the dataset

The raw dataset contains information about the properties sold in Victoria, which can be described as follows:

|COLUMN |DESCRIPTION|
|---|---|
|ID| A unique id for the property|
|Address| The property address|
|Price| The property price|
|Type| The type of property|
|Date|Date of sold|
|Rooms|Number of bedrooms|
|Bathroom|Number of bathrooms|
|Car|The number of parking space of the property|
|LandSize|The area of the propert|
|Age|The age of the property at the time of selling|
|Latitude|The Latitude of the property|
|Longitude|The Longitude of the property|

# External data

**gtfs.zip** - Contains the information on travel schedules and routes for trains (PTV) in Victoria.

**vic_suburb_boundary** - Includes shape file of Victoria with suburb boundries and their location.

**council.txt** - Contains information of suburbs for each council.

**crimebylocationdatatable-yearending31march2016.xlxs** - contains all crimes data for VIC.

**school-ranks.html** - Comprises of the information on school ranks.

**schools.xml** - This xml file includes data about schools, their types and locations.  

# Environment setup

Install all packages required to run this program as follows in the environment where you are running this notebook/cloning this repo:

```
pip install -r requirements.txt
```

Run each cell of the notebook.
