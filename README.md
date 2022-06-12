# Lead-Scoring-Logistic-Regression
## Problem Statement : 
Our client X Education sells online courses to industry professionals. Professionals visit their website and explore available online course on a daily basis. Our client promotes their website and courses on varoius websites as well as on several search engines like Google, Bing, Yahoo etc. using ad campaigns in which the interested target audience and potential customers fill a form or watch a promotional video and share their contact details like phone number and email ids for furthur information and discussion. Those customers are knows as Leads Also, Word-of-mouth marketing plays a huge role in lead generation for our client.

Employees from the sales team approach these leads via emails, phone calls, text messages etc. Some of these leads, around 30% in our client's case, are converted which is a very poor conversion rate.

There are a lot of leads generated in the initial stage (social media marketing and search engine marketing) but only a few of them come out as paying customers from the bottom. If we demonostarte the entire process in a diagram and keep the 1st step on top and converted leads at bottom it would look like a funnel. In the middle stage, we nurture the potential leads well (i.e. educating the leads about the product, constantly communicating etc. ) in order to get a higher lead conversion.

So, to make this process more efficinet the X education company wants to identify the most potential leads, also, known as Hot Leads. If they successfully identify this set of leads, the lead conversion rate should go up as the sales team will now be focusing more on communicating with the potential leads rather than making calls to everyone.

Our job here is to help them select the most promising leads, i.e. the leads that are most likely to convert into paying customers.

Our Goals in Layman's Language : To build a model wherein you need to assign a lead score to each of the leads such that the customers with higher lead score have a higher conversion chance and the customers with lower lead score have a lower conversion chance. The CEO, in particular, has given a ballpark of the target lead conversion rate to be around 80%.

## Data : 
We have been provided with a leads dataset from the past which consists of various attributes such as Lead Source, Total Time Spent on Website, Total Visits, Last Activity, etc. which may or may not be useful in ultimately deciding whether a lead will be converted or not.

The target variable, in this case, is the column ‘Converted’ which tells whether a past lead was converted or not wherein 1 means it was converted and 0 means it wasn’t converted.

We also need to check out for are the levels present in the categorical variables. Many of the categorical variables have a level called 'Select' which needs to be handled because it is as good as a null value. SO, we may have to replace them with 'Nan'.

## Goals : 
There are quite a few goals for this case study.

We need to build a logistic regression model to assign a lead score between 0 and 100 to each of the leads which can be used by the company to target potential leads. A higher score would mean that the lead is hot, i.e. is most likely to convert whereas a lower score would mean that the lead is cold and will mostly not get converted. There are some more problems presented by the company which our model should be able to adjust to if the company's requirement changes in the future.So we will fill these problems which are provided in a separate doc file. It should be based on the logistic regression model we got in the first step. Also,we need to include this in our final PPT where you'll make recommendations.

## Steps to follow:

- Reading and Understanding the Data
- Data Cleaning
- Exploratory Data Analysis
- Data Preparation
- Model Building
- Model Evaluation
