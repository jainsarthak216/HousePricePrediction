# Azure project deploy
## House Price Prediction

This project help to find a price for property based on the geographical variables by breaking down past market patterns and value ranges and coming advancements future costs will be anticipated .

### Overview :
First of all we have to download dataset from kaggle . Then we have to apply feature engineering into dataset to clean the data , feature scaling , data pre-processing and like many more things . Then we have to divide our dataset into two part , first part says independent feature and dependent feature . In dependent feature we consider price and independent feature consider rest of the column . Then we have to divide dataset into two part, first part train dataset and second part test dataset . Then after we have to apply some regression model to train the data . After that we have test the model and check the accuracy of model .After checking the models I have conclude that the linear regression model is best for this project and the accuracy of the linear regression model is 88% .

After creating the model we have to deploy our Linear regression model into web application . For that purpose I have use python framework Flask . Basically Flask has use to connect Linear regression model with HTML , CSS , Javascript code .

For additional , I have add a chatbot in this web application . This chatbot is created using IBM Watson Assistant .

### Deployment :
To deploy the project on Azure portal, I followed the following documentaion - https://docs.microsoft.com/en-us/azure/app-service/ .
1. Created a new resource group .
2. Made and configured a new web app resource by using Azure Web App service .
3. In the resource deployment center, I set the source as Github and selected the project repository from my Github account.
4. Finally, I deployed the mentioned Github repository .

### Tools & Technology
Technology — Jupyter notebook
Language — Python

### Conclusion :
In this project I have learn about how to load dataset , how to apply feature engineering , how to fit model into dataset , how to check accuracy of model , and like many more things that I have learn doing this project .

## Github Link :
https://github.com/jainsarthak216/HousePricePrediction

## Web App Link (Deployed on Azure)
http://houseprice.azurewebsites.net

