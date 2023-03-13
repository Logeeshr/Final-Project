# Final-Project
# Insurance_purchase_customer_conversion
# Customer Conversion prediction using Machine Learning Algorithms
## Promblem Statement

#### You are working for a new-age insurance company and employ mutiple outreach plans to sell term insurance to your customers. Telephonic marketing campaigns still remain one of the most effective way to reach out to people however they incur a lot of cost. Hence, it is important to identify the customers that are most likely to convert beforehand so that they can be specifically targeted via call. We are given the historical marketing data of the insurance company and are required to build a ML model that will predict if a client will subscribe to the insurance. 

## Dataset
 ### Features
 1. Age (age of person)
 2. Job (type of job)
 3. Marital (marital status)
 4. educational_qual (education status)
 5. call_type (contact communication type) 
 6. day:last contact day of the month (numeric) 
 7. mon: last contact month of year
 8. dur: last contact duration, in seconds (numeric)
 9. num_calls: number of contacts performed during this campaign and for this client
 10. prev_outcome: outcome of the previous marketing campaign (categorical: "unknown","other","failure","success")
 
 ### Target 
 11. Y - has the client subscribed to the insurance?(YES/NO)
 
 ## Work flow 
 
 1. Data Collection
 2. Data importing
 3. Data cleaning
 4. Exploratory Data Analysis
 5. Feature Engineering
 6. Model Building
 7. Deployment
 
 ## Machine learning Algorithm Used
 
 1. Logistic Regression
 2. K-Nearest Neighbour
 3. Decision Tree classification
 4. Random forest classification
 5. XGBoost classification
 
  ### Evaluation metrics used for calculating the Performance of model:
  1. AUROC Score
  2. Accuracy Score
  3. Classification report
  
  
  ## Deployment
  ### Attached Screen shots of web app 
  ![Cus1](https://user-images.githubusercontent.com/115647490/224844129-4da88df8-34f7-484c-a467-87f223f18f7c.PNG)
  ![Cus 2](https://user-images.githubusercontent.com/115647490/224844234-be05334e-9d11-4179-8218-c58e6e282c0f.PNG)
  ![Cus3](https://user-images.githubusercontent.com/115647490/224844418-221edc97-0f89-48ae-be8a-07688c9e2a36.PNG)
  ![Cus 4](https://user-images.githubusercontent.com/115647490/224844558-2e3b8d9f-536d-43a3-99d7-adfe6a07675d.PNG)
  
  ##-------------------------------------------------------------------------------------------------------------------------
  
  # Item Demand Forecasting to Maximize profit and Minimise lose
## Promblem Statement
#### Demand forecasts are fundamental to plan and deliver products and services. Accurate forecasting of demand can help the manufacturers to maintain appropriate stock which results in reduction in loss due to product not being sold and also reduces the opportunity cost (i.e. higher demand but less availability => opportunity lost). Despite such relevance, manufacturers have difficulty choosing which forecast model is the best for their use case. In this project, historical sales data corresponding to multiple(25) items sold in 10 stores are provided and participants are expected to come up with a best model to predict the future demand for products which results in maximum profit for the manufacturer.Predict the demand for the next 3 months at the item level (i.e. all the stores combined).


## Dataset
##### The dataset used is given by Guvi for Educational Purposes
##### The columns in the dataset
1. Date  -----> Date on which the items are sold
2. Store -----> Store on which Items are sold
3. Item  -----> 50 unique Items
4. Sales -----> Sales of every Item

## Workflow
1. Imporing Libraries
2. Data Wrangling
3. Exploratory Data Analysis
4. Feature Engineering
5. Model Building
6. Evaluation metrics

## About Project
##### In this project, the main aim is to predict the next 3 month Sales on item level from a particular Date. So I found the rolling sum for a window 90 days and predicted the Sales.In Model Building I used Decision tree Regressor, Random Forest Regressor, Linear Regression, XG Boost, KNN Regresoor are used. In that XG Boost performed well Compared to other model.



  
