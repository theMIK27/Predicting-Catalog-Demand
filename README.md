# Predicting-Catalog-Demand
Project 1- Predictive Analytics for Business Nanodegree

# Overview
In this project, you will analyze a business problem in the mail-order catalog business. You're tasked with predicting how much money your company can expect to earn from sending out a catalog to new customers. This task will involve building the model and applying the results in order to provide a recommendation to management.

# The Business Problem
You recently started working for a company that manufactures and sells high-end home goods. Last year the company sent out its first print catalog, and is preparing to send out this year's catalog in the coming months. The company has 250 new customers from their mailing list that they want to send the catalog to.
Your manager has been asked to determine how much profit the company can expect from sending a catalog to these customers. You, the business analyst, are assigned to help your manager run the numbers. While fairly knowledgeable about data analysis, your manager is not very familiar with predictive models.
You’ve been asked to predict the expected profit from these 250 new customers. Management does not want to send the catalog out to these new customers unless the expected profit contribution exceeds $10,000.

# Details
The costs of printing and distributing is $6.50 per catalog.
The average gross margin (price - cost) on all products sold through the catalog is 50%.
Make sure to multiply your revenue by the gross margin first before you subtract out the $6.50 cost when calculating your profit.

# Steps
Step 1: Business and Data Understanding
Your project should include:
A description of the key business decisions that need to be made.

Step 2: Analysis, Modeling, and Validation
Build a linear regression model, then use it to predict sales for the 250 customers.I used Alteryx to build the best linear model with data.

Once you have your linear regression equation, you should use your linear regression equation to predict sales for the individual people in your mailing list.

Step 3: Writeup
Once you have your predicted or expected profit, write a brief report with your recommendation to whether the company should send the catalog or not.

# Data
p1-customers.xlsx - This dataset includes the following information on about 2,300 customers. 
Important: We have to build our model on this dataset and not p1-mailinglist.xlsx.

p1-mailinglist.xlsx - This dataset is the 250 customers that you need to predict sales. This is the list of customers that the company would send a catalog to. Use this dataset to estimate how much revenue the company can expect if they send out the catalog. It includes all of the fields from P1_Customers.xlsx except for Responded_to_Last_Catalog so this variable cannot be used in the linear regression model since it could not be applied to the mailing list data set. It also includes two additional variables.

Score_No: The probability that the customer WILL NOT respond to the catalog and not make a purchase.
Score_Yes: The probability that the customer WILL respond to the catalog and make a purchase.

# Suggestions
When you are thinking about what decisions need to be made and what data is needed consider the following:
What is the company ultimately trying to make a decision on? 
What is the criteria that will let them know what they should decide? 
How will we predict the potential profit of sending out the catalog? 
Considering the data we have, what pieces of it may be useful in coming up with this prediction?

Low P-values and a high R-squared suggest the model is highly predictive, Low P-values means it is highly unlikely that the two variables are not related. Low R squared means the model is not very fit.
