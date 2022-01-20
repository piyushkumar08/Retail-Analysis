# Retail Analysis with Walmart Data

1. [Project Motivation](#ProjectMotivation)
2. [Installation](#installation)
3. [Data](#data)
4. [Implementation](#model)
5. [Results](#results)

## 1. Project Motivation <a name="ProjectMotivation"></a> 

**In this project we focused retail analysis with Walmart data and answer the following questions:**
1. Which stores have maximum  and sales?
2. Which store has maximum standard deviation i.e., the sales vary a lot?. Also, find out the coefficient of mean to standard deviation.
3. Which store/s has good quarterly growth rate in Q3’2012?
4. Find out holidays which have higher sales than the mean sales in non-holiday season for all stores together.
5. Provide a monthly and semester view of sales in units and give insights.
6. Build prediction to forecast demand.


## 2. Installation <a name="installation"></a>

- R-Studio
- R-libraries :
  - caTools
  - dplyr
  - ggplot
  - forecast
  - lubridate
  - tsbox 
  

## 3. Data<a name="data"></a> 

There are sales data available for 45 stores of Walmart. This is the data that covers sales from 2010-02-05 to 2012-11-01.
Also uploaded above by the name : "Walmart_Store_sales.csv"


## 4. Implementation <a name="model"></a> 
Before modellling, Outlier Testing is done to remove all the outliers for different variables. After that, the data have been split into training and testing with a ratio of 70:30. Modelling is done on train data and after that testing is performed.

## 5. Result<a name="results"></a>
Click [here](https://github.com/piyushkumar08/Retail-Analysis/blob/main/Retail-Analysis_Insights.pdf) to check out the results.
