# Neural_Network_Charity_Analysis
## Overview
Dataset provided with more than 34,000 organizations that have received funding from Alphabet Soup over the years is used to help create a binary classifier that is capable of predicting whether applicants will be successful.

## Resource
"Resources/charity_data.csv" columns contain:
-EIN and NAME—Identification columns
-APPLICATION_TYPE—Alphabet Soup application type
-AFFILIATION—Affiliated sector of industry
-CLASSIFICATION—Government organization classification
-USE_CASE—Use case for funding
-ORGANIZATION—Organization type
-STATUS—Active status
-INCOME_AMT—Income classification
-SPECIAL_CONSIDERATIONS—Special consideration for application
-ASK_AMT—Funding amount requested
-IS_SUCCESSFUL—Was the money used effectively

## Results
A model is created and optimized by preprocessing the dataset for a neural network, compiling, training and evaluating the model for this project.

Columns EIN and NAME—Identification were dropped as neither being targets nor features. IS_SUCCESSFUL was used as a target variable. And features were the other columns highlighted by CLASSIFICATION and APPLICATION_TYPE. The columns with more than 10 unique values have been grouped together; the categorical variables have been encoded using one-hot encoding; the preprocessed data is split into features and target arrays; the preprocessed data is split into training and testing datasets; and the numerical values have been standardized using the StandardScaler() module.

The model is made with an input features, two hidden layers and activation functions. The hidden layer 1 with 80 neurons("relu"), the layer 2 with 30 neurons("relu"), with an output layer as "sigmoid".

![image](https://user-images.githubusercontent.com/71358697/108940894-ff4d3d00-7608-11eb-9ad5-9750477b23b5.png)
![image](https://user-images.githubusercontent.com/71358697/108940908-0411f100-7609-11eb-9bd4-5c576d1c9936.png)

In an attempt to optimize the model is made with an input features, two hidden layers and activation functions. The hidden layer 1 was changed to 16 neurons("relu"), the layer 2 with 8 neurons("relu"), with an output layer as "sigmoid" and saved as "AlphabetSoupCharity.Opt.h1".

![image](https://user-images.githubusercontent.com/71358697/108940912-06744b00-7609-11eb-8449-91f2ad94e23d.png)
![image](https://user-images.githubusercontent.com/71358697/108940920-096f3b80-7609-11eb-8d5d-b21c623445d3.png)

In an attempt to optimize the model is made with an input features, two hidden layers and activation functions. The hidden layer 1 was changed to 40 neurons("relu"), the layer 2 with 25 neurons("relu"), with an output layer as "sigmoid" and saved as "AlphabetSoupCharity.Opt.h2".

![image](https://user-images.githubusercontent.com/71358697/108940935-0c6a2c00-7609-11eb-84af-a2712583c6fd.png)
![image](https://user-images.githubusercontent.com/71358697/108940946-0ecc8600-7609-11eb-9521-b9e869656ac9.png)

In an attempt to optimize the model is made with an input features, two hidden layers and activation functions. The hidden layer 1 was changed to 100 neurons("relu"), the layer 2 with 50 neurons("relu"), with an output layer as "sigmoid" and saved as "AlphabetSoupCharity.Opt.h3".

![image](https://user-images.githubusercontent.com/71358697/108940953-11c77680-7609-11eb-8506-a3a00a05c29a.png)
![image](https://user-images.githubusercontent.com/71358697/108940960-13913a00-7609-11eb-8b59-af6c18147c87.png)

In an attempt to optimize the model is made with an input feature, changing to three hidden layers with activation functions. The hidden layer 1 was changed to 55 neurons("relu"), the layer 2 with 75 neurons("relu"), and layer 3 with 24 neurons("linear") with an output layer as "sigmoid" and saved as "AlphabetSoupCharity.Opt.h4".

![image](https://user-images.githubusercontent.com/71358697/108940966-168c2a80-7609-11eb-96cb-d34f95ab35ef.png)
![image](https://user-images.githubusercontent.com/71358697/108940968-19871b00-7609-11eb-9954-eb2eb1aa82ec.png)

