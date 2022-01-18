# Azure project deployment

## Heart Disease Predictor
This project helps to predict whether a person has heart disease or not using certain medical parameters given to the system.

## Overview :
First,we download the dataset from UCI repository . Then we have to apply feature engineering into dataset to clean the data , feature scaling , data pre-processing and find correlation between different features. Then we divide our dataset into two parts , independent features and dependent feature . In dependent feature we consider target and independent feature consider rest of the column . Then we divide the dataset into two sets, first part train dataset and second part test dataset . After that we choose an algorithm for classification and then train it and perform hyperparameter tuning.

After creating the model we have to deploy our Classification model into web application . For that purpose we use a Python framework called Flask . Flask is basically used to link our model with templates made using HTML and CSS. Different app routes are also created in our app.py file.


## Deployment :
To deploy the project, We follow this documentaion - https://docs.microsoft.com/en-us/azure/app-service/ .

Created a new resource group .
Made and configured a new web app resource by using Azure Web App service .
In the resource deployment center, We set the source as Github and selected the project repository from my Github account.
Finally, We deploy the mentioned Github repository . We then test our project by giving the medical parameters to the web app and submit the form. At the bottom of the page, 0 is displayed if the person dosen't have heart disease. 1 is displayed if the person has heart disease.


## Conclusion :
In this project We have learnt about how to load dataset , how to apply feature engineering ,how to find feature correlation, how to fit model into dataset , how to check accuracy of model , how to do hyperparameter tuning, how to deploy our web app and many more things.

## Github Link :
https://github.com/Tushar00728/Heart-Disease-predictor-Azure

## Web App Link (Deployed using Azure portal)
http://heartdiseasepred.azurewebsites.net/ (May take 5 minutes to load up).
