List of Projects in this Portfolio

1. Air Traffic is Still Safe
2. Analyzing Customer Churn in the Telecommunication Industry
3. Brand Sentiment Analysis
4. Los Angeles Crime Rates
5. Predicting American Airlines Stock Prices
6. Predicting Car Insurance Premium
7. Predicting Naval Vessel Condition for the Purpose of Preventative Maintenance
8. Predicting the Quality Categories of Apples from Numerical Features Using Neural Networks and Decision Trees
9. Selecting Startup Inventory for a New Chain of Beer Stores
10. Titanic Survival


Description

1. Air Traffic is Still Safe (DSC 640)

This project was about finding and presenting data that allows the airline industry to reassure the public that flying is still safe after a set of widely publicized airline crashes. Various datasets were provided, and I chose one dataset about airline accidents going back several decades, as well as a supplemental dataset about motor vehicle crashes, to compare the safety records of both modes of transportation. The initial part of the project, as shown here, was the data visualization I did in Jupyter Notebook.

2. Analyzing Customer Churn in the Telecommunication Industry (DSC 630)

Based on a Kaggle dataset about customer churn in the telecommunication industry, my team and I attempted to determine how telco companies can reduce customer churn. To do so, we first did an EDA to see what data was in the dataset and how it needed to be cleaned and prepared for the next steps in the analysis. After the cleaning, we did some feature engineering by creating dummy columns, as well as reformatting yes/no columns to binaries. We used a logistic regression model and random forest regressor to determine feature importance and, based on that, recommend what the telcos should concentrate on to reduce customer churn.

3. Brand Sentiment Analysis

This project analyzes a brand name (or any query string yielding Google News results) by gauging sentiment across about 100 news articles. It gathers URLs via BeautifulSoup, calculates sentiment scores using TextBlob, and aggregates these scores. Results include average sentiment, counts of positive, neutral, and negative articles, and a pie chart illustrating brand sentiment.

4. Los Angeles Crime Rates (DSC 540)

In this project, I took three individual datasets and added them as tables to a MySQL database. I used the mysql_connector package to enable Python in my Jupyter Notebook to access my locally hosted MySQL database server. Using several custom helper functions, I loaded the three datasets into the database. After, I decided on which visualizations I wanted to make and which data I would need for them. I used SQL queries to collect the data from one or more tables into Python data frames and then visualized them using Matplotlib.

5. Predicting American Airlines Stock Prices (DSC 680_Project2)
   
This project was about finding a way to predict short-term stock price changes in American Airlines stock by using other airline stock prices and/or vendor stock prices, as well as economic indicators and/or resource prices (i.e., fuel). It included exploratory data analysis (EDA), data preparation, and model evaluation. The linked Jupyter Notebook shows all parts of this project, including the final model evaluation and recommendation.

6. Predicting Car Insurance Premium

The objective of this project is to leverage data-driven approaches and predictive modeling techniques to develop a robust framework for estimating car insurance costs. By analyzing historical data and identifying patterns within various attributes, I aim to build a predictive model that accurately forecasts insurance premiums based on individual characteristics. This predictive model will enable insurance companies to streamline their underwriting processes, optimize pricing strategies, and offer competitive premiums tailored to each customer's risk profile.

7. Predicting Naval Vessel Condition for the Purpose of Preventative Maintenance (DSC 680_Project3)
  
This project dives into maintenance and operational data collected from the engine rooms of naval vessels to derive the current decay state coefficient of both the gas turbine and the gas turbine compressor of the vessel propulsion system. The final model was able to predict the decay state coefficient with an accuracy of 99%. If this model were to be used in real-time on a gas turbine-powered naval vessel, it could substantially lower the risk of at-sea breakdown by allowing maintenance well in advance of potential breakdown, but not unnecessarily early.

8. Predicting the Quality Categories of Apples from Numerical Features Using Neural Networks and Decision Trees

This project created a model to predict the quality category (good/bad) of apples based on numerical features, such as sweetness and crunchiness. By using this model, growers can successfully classify their apples for certain uses. The final model was able to predict the quality category with an accuracy of 91%.

9. Selecting Startup Inventory for a New Chain of Beer Stores (DSC 680_Project1)

This project was about a fictitious new chain of beer stores that needed a good startup inventory. My goal was to predict which beers the store should stock in order to have the best chance of success (i.e., good sales). I used a Kaggle dataset containing data about beer reviews. It contained information about the types of beers and the features/properties of the individual beers. I did an EDA to determine what information could be gleaned from the dataset and what cleaning and preparation would need to be done. Once the dataset was cleaned and ready for further analysis, I used a random forest regressor to determine feature importance, then calculated the most popular beer types and beers within the types, and finally produced a list of 30 styles of beers with 20 beers in each for the stores to use.

10. Titanic Survival (DSC 530)

Using a dataset with information about the passengers of the Titanic disaster, I did an analysis to determine what the primary factors for surviving the sinking were. I did an initial EDA to get an idea of what the data holds and what needs to be cleaned up and prepared for the analysis. I then used the chi-square test to see which variables had a strong association with survival, and I did both a multi-nominal logistic regression and a linear regression to predict the most important factors for survival.
