Using AirBnB-Seattle-Data set to predict the listing price
Medium URL link for this project:  
https://medium.com/@ali.balati/how-well-the-linear-regression-model-predicts-the-housing-prices-fbf4973b0acf 
In this project, I am going to perform a standard data analysis procedure to extract useful information and subsequently I will try to answer related questions. Finally, I will build a linear regression model to predict the lighting prices.  
Context
Since 2008, guests and hosts have used Airbnb to travel in a more unique, personalized way. As part of the Airbnb Inside initiative, this dataset describes the listing activity of homestays in Seattle, WA.
Content
The following Airbnb activity is included in this Seattle dataset:
•	Listing prices along with the details 
•	Reviews, including unique id for listings
•	Calendar, including listing id and the price and availability for that day
Installation
The data analysis for this project was performed using Python 3.8. Specifically, in Jupyter Notebooks platform. The following major libraries were used for the dataset analysis and visualization:  numpy, pandas, sklearn, matplotlib and seaborn. 
Project Motivation
The Seattle data set is a great free and available source for analyzing a big dataset Everyone who wants to hone the coding and data analysis can definitely benefit from. The main motivation for myself was getting started with analyzing real dataset. This project is part of my Udacity data science project where I tried to answer the following questions: 
1.	 What is the typical price for a listing and what are the minimum and maximum revenue?
2.	what is the distribution of typical listing prices?
3.	How good our model is in predicting listing price?
File Descriptions:
For the data analysis and visualization, I focused mainly on AirBnB Dataset listing price data set and the major goal of the analysis was cleaning dataset, extract useful insights and finally predicting the price based upon linear regression analysis.   
Result
As per what recommend through my data science classes, I tried to stick to CRISP-DM procedure.  I found that a significant difference in mean and median in pricing of the listing dataset! Statistically speaking, the mean is a good representative of the normally distributed data while, the median is best one when the data distribution is skewed. This result indicate that our analysis of listing price should be heavily focused on the median. Despite of a few outliers on the higher end, the vast majority of listing price are not more than 200 USD with of approximately 127 USD and median 100 USD, respectively. After performing data cleaning by data imputation and also encoding categorical values as numbers, I decided to remove neighborhood column as a categorical variable from my dataset given that neighborhood columns was diluting the variability in the dataset. This particular column was creating way more dummy columns. Additionally, I normalized the data before training the model. I evaluated the linear regression models performance suing R-squared (R2) and Root Mean Squared (RMS). As per calculated R2 more than % 85 of the observed variation in listing prices can be explained by the model’s inputs. Moreover, quality of the model fit was determined by RMS, which was obtained to be equal 35.1. 

Medium Blog
https://medium.com/@ali.balati/how-well-the-linear-regression-model-predicts-the-housing-prices-fbf4973b0acf 
Acknowledgement
I have a very positive experience with the Udacity learning platform so far. Specifically, I really appreciate the mentors who were really responsive and had a quick response time for my questions. 

