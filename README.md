# Churn Rate

## Dataset Description:
- Dataset Name: Customer_Churn_Prediction
- Data Source: Sony Research
- Data Collection Date: --
- Data Collection Method: --

## Data Fields:
- `State` : The state where a customer comes from (string)
- `International plan` : The status of customer international plan (string)
- `Voicemail plan` : The status of customer voicemail plan (string)
- `Account length` : Number of days a customer has been using services (integer)
- `Area code` : The area where a customer comes from (integer)
- `Phone number` : The phone number of a customer (Alphanumeric)
- `No. vmail msgs` : Number of voicemail message sent by a customer (Integer)
- `Total day minutes` : Total call minutes spent by a customer during day time (float)
- `Total day calls` : Total number of calls made by a customer during day time (integer)
- `Total day charge` : Total amount charged to a customer during day time (float)
- `Total eve minutes` : Total call minutes spent by a customer during evening time (float)
- `Total eve calls` : Total number of calls made by a customer during evening time (integer)
- `Total eve charge` : Total amount charged to a customer during evening time (float)
- `Total night minutes` : Total call minutes spent by a customer during night time (float)
- `Total night calls` : Total number of calls made by a customer during night time (integer)
- `Total night charge` : Total amount charged to a customer during night time (float)
- `Total intl minutes` : Total international call minutes spent by a customer (float)
- `Total intl calls` : Total number of international calls made by a customer (integer)
- `Total int charge` : Total international call amount charged to a customer (float)
- `Customer service calls` : Total number of customer service calls made by a customer (integer)
- `Churn` : Whether a customer is churned or not (boolean)

## Data Preprocessing:
- Missing Values: No missing values in the dataset.
- Data Cleaning: NA
- Feature Engineering: One-hot encoding for `area code`.
- Data Transformation:
- Assumptions:

## Data Format:
- CSV file format

## Access Permissions:
- The dataset is accessible to StrataScratch users for analysis purposes. Access is limited to authorized personnel only.

## Version Information:
- Version 1.0 (Initial release)
