#  AI4Good Challenge : Exploring the Impact of COVID-19 & Our Solution
This was a Hacakthon project for AI4Good. Two models were built based on Centraide sponsored call data and Montreal open datasets addressing how public organizations and private businesses can adjust to improve their services in light of the impact of COVID-19.

Presentation : https://docs.google.com/presentation/d/1ZrEiKIcTpAlUfM3sfEQqWX1AEPLISoAFgGX0zCcY-fs/edit#slide=id.gab1c3f1510_1_0

Result: Winner - Most actionable for Montreal

## Inspiration
To provide useful solutions we first needed to understand the issues at hand. That mindset drove our team to explore how the status of businesses across Greater Montreal has affected the needs of the citizens that request Centraide's services. Along with the coaching of AI experts gathered at the 2020 Hackathon, we propose a solution to predict future impact of bankruptcy of for-profit and non-for-profits businesses. 

## What it does
We visualized an external dataset related to business closures in Montreal (Montreal Open Datasets - J'informe les commerçants) using Data Studio as well as used a time series to explore the needs of Montreal citizens. 

1. We have created a tree based model for predicting status of Montreal businesses based on Montreal questionnaire dataset.

2. The second model aims to predict the number of calls made any day by the hour based on the need category e.g if you choose now as the day and time, the model will predict how many calls you can receive in that hour for each category. This will enable you to efficiently scheduled the number of people you need every hour to attend to a particular need category.

## How we built it

#### Model 1
We have built the first model using XGBoost algorithm in python.
Process:
 - Cleaning the data using pandas
 - One hot encoding of the categorical variables
 - Feature selection and feature importance table
 - Using XGBoost Classifier model
 - Fine tune hyperparameters and feature engineering for better performance

####Model 2

We built it using scikit-learn's Randomforest Algorithm.Numeric features were scaled using StandardScaler while categorical features were encoded using one-hot encoding. We build a complete pipeline that takes the raw data, process it and make predictions.

## Challenges we ran into
A consensus of the main direction we wanted to take this project was a huge undertaking.
Language barriers to understand the data, conflicts of interests and asynchronous communication were all factors that reduced our collaborative drive.
However, through the help of mentors such as Olivier Foster, Nithum Thain, Mathieu Chaurette as well as more in-depth exploration of external open datasets available, we were able to resolve our struggles.
Also a lot of time was spend looking for good datasets. We have looked at housing prices datasets, criminal/justice datasets, business closure etc.

## Accomplishments that we're proud of

Provided visualizations https://datastudio.google.com/s/ooaOE-QNrZ8 and a tool that members of Centraide and other organizations for social good can use to improve their services and be more informed about how they can prepare themselves to support their communities.

We produced working model to predict the business statuses based on questionnaire.



## What we learned

Working on this hackathon had plenty of challenges.
One of the main issue was this is held online and there was less in person communication. As a result of this sometimes we lacked the direction. 
In the end we were able to come together and answer some of the key questions and produce a working model.

## What's next for Team Star & Exploring the Impact of Covid19 in Montreal?
We look forward to the next hackathon!
