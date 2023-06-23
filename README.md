# Catching The Fraudsters!!!

# Project Overview

Our project will be to create a machine learning model that can accurately predict if a claim application is fraudulent or not. Insurance fraud occurs when "someone puts false information on an insurance application and when false or misleading information is given or important information is omitted in an insurance transaction or claim" (Arizona Department of Insurance and Financial Institutions, 2019).
This can be useful to insurance companies in avoiding costs they normally do not have to incur. 

# Data Source
Data was sourced from www.kaggle.com and was updated a year ago. This data shows many features, the chosen target variable of “FraudFound_P”.

# Data Features

Some features not relevant to our study were dropped from the original data set and included: 'PolicyNumber', 'RepNumber, 'Days_Policy_Claim', 'Days_Policy_Accident', 'Make','NumberOfSuppliments', 'DriverRating', 'PolicyType', 'AgentType'. 

'Month': Month of year when the accident happened
'WeekOfMonth': Week of month when the accidennt happened
'DayOfWeek': Day of week when the accident happened
'AccidentArea': Location where the accident happened
'DayOfWeekClaimed': Day of week when claim on accident was made
'MonthClaimed': Month of year when claim on accident was made
'WeekOfMonthClaimed: week of month when the claim was made
'Sex': sex of driver 
'MaritalStatus': marital status of driver 
'Age': age of driver 
'Fault': Wether the policy holder or the other party was at fault
'VehicleCategory': Type of vehicle body
'VehiclePrice': Price of vehicle involved in accident
'FraudFound_P': Whether a fraud was detected 
'Deductible': How much their dedictble was 
'PastNumberOfClaims': number of claims made by this policy holder in the past
'AgeOfVehicle': Age of vehicle involved in accident
'AgeOfPolicyHolder': lStatus': marital status of driver 
'Age': age of policy number 
'PoliceReportFiled': Wether a police report where filed or not
'WitnessPresent': Wether a witness was present 
'AddressChange_Claim': whether the policy holder changed a
'NumberOfCars': Number of cars under policy holder 
'BasePolicy': Type of coverage hold by policy holder
  
  
# Possible Machine Models

Linear Regression
PCA
neural network
KNN
SVM

# Results and Summary of the application

Models appear to have the same accuracy. More work needs to be done to be able to compare all the models used based on recalls.