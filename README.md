# Kaggle 'Predict Future Sales': Project Overview (TOP 1%)
In this competition the objective was to predict future sales for a Russian firm 1C Company. The prediction should contain next month sales for 5100 items at each of the 42 shops, with predictions being clipped into the range (0,20). The performance metric was RMSE. To inform these predictions we were given sales data covering the 33 months prior to the test period. 

**At the end I reached a very good score with an RMSE of only 0.85256 witch put me in the top 1% of the competition.**

Attention: Since the file was too big, if you want to run this code you will need to start with the data preprocessing file in order to get the complete dataframe for the modeling part.

## EDA
In this step I analysed the data and took note of some preprocessing that could be done.

## Data Preprocessing
Some of the steps I took while preprocessing the data were:

* Preparing Item/Category Information
* Preparing Sales Information
* Constructing Training Dataframe
* Adding Shop Information
* Ages & Aggregating Sales/Price information
* Lagging Values & Features that use Prior Information
* Encoding Name Information 

## Model Building 
To make the prediction I used the LightGBM algorithm and it worked great!
