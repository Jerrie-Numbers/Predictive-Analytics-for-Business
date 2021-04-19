# Predictive-Analytics-for-Business
Projects of Predictive Analytics for Business Nanodegree at Udacity

### Summary

Apply predictive analytics and business intelligence to solve real-world business problems.
Over the program, with **Alteryx** and **Tableau**:

- Create mental models to clearly define business issues
- Visualize and prepare data to improve efficacy of predictive models 
- Identify and implement a variety of predictive modeling techniques
---

### Proejct 1 Predict Sales for a Catalog Launch

Build a linear regression model to provide results and a recommendation.

---

### Project 2  Create an Analytical Dataset
Use data preparation techniques (Alteryx) to build a robust analytic dataset and use it to build a predictive model to select the best location.

**The Business Problem**

Pawdacity is a leading pet store chain in Wyoming with 13 stores throughout the state. This year, Pawdacity would like to expand and open a 14th store. Your manager has asked you to perform an analysis to recommend the city for Pawdacity’s newest store, based on predicted yearly sales.

**Project Details**

 - Build the model, and select predictor variables 
 - Format and blend together data from different datasets and deal with outliers.

--------

### Project 3 Predict Loan Default Risk
Build and apply a classification model to provide a recommendation on which loan applicants the bank should lend to.

**The Business Problem**

You work for a small bank and are responsible for determining if customers are creditworthy to give a loan to. Your team typically gets 200 loan applications per week and approves them by hand. Your manager wants you to figure out how to process all of these loan applications within one week.

**Project Details**

 - Business and Data Understanding
 - Explore and Cleanup the Data
 - Train Classification Models: <br />
```
                 Logistic Regression 
                 Decision Tree
                 Forest Model
                 Boosted Tree 
```
---
### Project 4 A/B Test a Menu Launch
Design and analyze an A/B test and write up a recommendation on whether the chain should introduce the new menu.

**The Business Problem**

Round Roasters is an upscale coffee chain with locations in the western United States of America. The new management team believes that a television advertising campaign is crucial to drive people into the stores with these new offerings.

To minimize risk, the management team decides to test the changes in two cities with new television advertising. Denver and Chicago cities were chosen to participate in this test because the stores in these two cities (or markets) perform similarly to all stores across the entire chain of stores; performance in these two markets would be a good proxy to predict how well the updated menu performs.

**Project Details**


 - Plan Analysis: Choose performance metrics, test period and granularity of data
 - Clean Data: aggregate the transaction data to the appropriate level and filter on the appropriate data ranges
 - Match Treatment and Control Units: Create the trend and seasonality variables, and use them along with other control variables to match two control units to each treatment unit. Conduct correlation analysis and choose control variables
 - Analysis and Writeup: Conduct A/B analysis and create a report outlining results and recommendations.

---
### Project 5 Combine Predictive Techniques

Use multiple analytical techniques to provide recommendations on how to expand grocery store chain.

**Task 1:  Determining Store Format - Segmentation and Clustering**

Company currently has 85 grocery stores and is planning to open 10 new stores at the beginning of the year. Currently, all stores use the same store format for selling their products, but the Company wants to introduce different store formats. The task is to provide analytical support to make decisions about store formats and inventory planning.

 - Determine the optimal number of store formats based on sales data, using **K-means clustering model**
-   Segment the 85 current stores into the different store formats.

**Task 2: Store Format for New Stores - Classification**

The grocery store chain has 10 new stores opening up at the beginning of the year. The company wants to determine which store format each of the new stores should have. The task is to determine the format using each of the new store’s demographic data.

-   Develop a model that predicts which segment a store falls into based on the demographic and socioeconomic characteristics of the population that resides in the area around each new store.
-   Train Classification models.  Compare a **Decision Tree, Forest**, and **Boosted model**.
-   Use the model to predict the best store format for each of the 10 new stores.

**Task 3: Forecasting Produce Sales - Time Series Analysis**

The task is to prepare a monthly forecast for produce sales for the full year of 2016 for both existing and new stores.

 - Data Aggregation
 - Perform ETS and ARIMA model, choose the most appropriate parameters and model for forecasting
 - Forecast produce sales for both existing stores and new stores based on assumptions
 - Create data visualizations to present actual sales and forecasting sales in Tableau
