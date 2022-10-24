# Harley_Davidson_Documentation

## Using Data Science to Determine Harley Davidson's Most Valuable Assets
In Business Analysis, it is fundamental to find KPI's (Key Performance Indicators) to make crucial decisions. While figuring out how to commence this capstone, I needed
a way to analytically prove such findings. There are many interconnected parts in Business Analysis, all of which have become more intricately connected as a result of
globalization.
![image](https://user-images.githubusercontent.com/19559713/197594555-b7e733ec-4570-4c76-912c-17b01d770f8a.png)


## The Dataset
As this is a Business Analysis problem, I wanted to explore what factors (KPI's) are responsible for higher (or lower) profits whenever transactions
take place. I chose a Harley Davidson dataset from Kaggle containing transactional information of the different motorcyle shipments that took place, including: Make of motorcyle,
number of motorcycles per shipment, price per motorcycle, city/country recipient and the date. I used these different factors to find a correlation between the dataset
and the highest earnings. The dataset is available [here](https://www.kaggle.com/datasets/deepanshugpt/harley-davidson-sales-data?select=HarleyDavidsonSalesData.xlsx).


## Data Wrangling
Having established the question at hand, the next step is Data Wrangling. Also known as Data Cleaning, Munging, etc., Data Wrangling requires for us to clean the data in order
for it to be interpretable not only for the Data Scientist, but, even more importantly, for the Machine Learning Models. There is no one size fits all method for 
Data Wrangling; it always depends on the quality of the unadulterated dataset. Thankfully, my Data Wrangling was relatively painless: I had to drop 1 unnecessary
column, checked for NaN (Not a Number) values and then I was good to go. The Data Wrangling notebook is available [here](https://github.com/ate2640/Harley_Davidson_Documentation/blob/main/Harley_Davidson_Capstone_Data_Wrangling.ipynb).

![image](https://user-images.githubusercontent.com/19559713/197595802-051f2cd9-f4ec-428b-8e1c-2fa8c0172fad.png)

## Exploratory Data Analysis
As one of the most important part of this project, Exploratory Data Analysis calls for the creation of a series of visuals to understand existing relationships among
the data and thus serves as our benchmarks when we corroborate our findings via Machine Learning. From a business perspective, there is a notable emphasis on Exploratory
Data Analysis, as it's necessary to make significant findings easily interpretable for non-savvy data personnel, responsible for approving (or denying) any business-related
decision. The EDA is available [here](https://github.com/ate2640/Harley_Davidson_Documentation/blob/main/Updated_Harley_Davidson_EDA.ipynb).

## Pre-Processing
In the pre-processing stage, we prepare the data for Machine Learning. The KPI's are the independent variables; the Profits column is my dependent variable, i.e.
the one that I want to predict. A step-by-step is available [here](https://github.com/ate2640/Harley_Davidson_Documentation/blob/main/Harley_Davidson_PreProcessing_Final.ipynb).

## Modeling
As this is a regression problem, i.e. we want to predict continuous values, I implemented a series of regression models, namely Random Forest, LASSO Regression and
OLS Regression. Implementing these regressions allowed for me to access the KPI's and find what categories of the dataset are most responsible for the highest revenue.
The Modeling steps and their respective results are available [here](https://github.com/ate2640/Harley_Davidson_Documentation/blob/main/Newest_Modeling_Harley_Davidson.ipynb).
