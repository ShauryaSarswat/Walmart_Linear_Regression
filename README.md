# <b> Walmart Data Regression 
 
# <b> Table of Contents </b>

- Problem Statement
    - Description
    - Objectives
    - How to achieve objectives
- Outcome
- Practical Results

# Problem Statement
<b> Description : </b>
<p align="center">
  <img src="https://www.pngplay.com/wp-content/uploads/9/Walmart-PNG-HD-Quality.png"/>
</p>
One of the leading retail stores in the US, Walmart, would like to predict the sales and demand accurately. There are certain events and holidays which impact sales on each day. There are sales data available for 45 stores of Walmart. The business is facing a challenge due to unforeseen demands and runs out of stock some times, due to the inappropriate machine learning algorithm. An ideal ML algorithm will predict demand accurately and ingest factors like economic conditions including CPI, Unemployment Index, etc.


Walmart runs several promotional markdown events throughout the year. These markdowns precede prominent holidays, the four largest of all, which are the Super Bowl, Labour Day, Thanksgiving, and Christmas. The weeks including these holidays are weighted five times higher in the evaluation than non-holiday weeks. Part of the challenge presented by this competition is modeling the effects of markdowns on these holiday weeks in the absence of complete/ideal historical data. Historical sales data for 45 Walmart stores located in different regions are available.


<b> Objectives : </b>
<p align="center">
  <img src="https://cdn-icons-png.flaticon.com/512/5307/5307748.png" width="150"/>
</p>

- Understand the dataset and cleanup
- Build regression models to predict the sales with refrence to single and multiple features
- Evaluate the models and compare their respective scores like R2, RMSE.

<b> How to achieve objectives :</b>

<p align="center">
  <img src="https://creazilla-store.fra1.digitaloceanspaces.com/cliparts/3868217/achievement-clipart-md.png" width="130px"/>
</p>

- Data Retrieval : walmart.csv
- Data Exploration and Cleaning
- Performing the EDA
- Feature Engineering
- Data Scaling and Modelling

# Outcome of Project
<p align="center">
  <img src="https://upraise.io/wp-content/uploads/2022/07/Output-Vs-OutcomeTop-10-Differences-Banner.webp" width="200px"/>
</p>


In this project, we analyzed and compared the performance of three different regression algorithms: Linear Regression, Decision Tree Regression, and Random Forest Regression. We used the Walmart Store's dataset to train and test the models, and evaluated their performance using mean squared error (MSE) and R-squared (R2) score.

Model Training and Testing

<p align="center">
  <img src="https://www.compliancequest.com/wp-content/uploads/2021/06/Benefits-of-CQ-Quality-Management-Training.png" width="200px"/>
</p>

We then trained and tested each regression algorithm on the standardized training and testing sets. For linear regression, we used scikit-learn's LinearRegression class. For decision tree regression, we used scikit-learn's DecisionTreeRegressor class with a maximum depth of 3. For random forest regression, we used scikit-learn's RandomForestRegressor class with 100 trees.

# Observations

<p align="center">
  <img src="https://static.thenounproject.com/png/2948637-200.png" width="200px"/>
</p>

| **Model** | **R2_Score** | **MSE** |
| --- | --- | --- |
| *Random Forest Regressor* | 0.9547956655361873 | 13832158045.8536 |
| *Decision Tree Regressor* | 0.45383248487028593 | 167122809756.95074 |
| *Linear Regression* | 0.1315480049548715 | 265739234814.2515 |

# Result


<p align="center">
  <img src="https://cdn.pixabay.com/photo/2018/12/05/08/44/win-3857339_1280.png" width="200px"/>
</p>

Random Forest was the most efficient algorithm for the given dataset.