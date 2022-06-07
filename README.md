# Data manipulation and Linear Regression

We did the Data manipulation and Regression and understand the upvotes on top reddit posts

Initial Setup

We install the PRAW library for scraping reddit data.

We completed the project in 3 parts which are described as below

## Part 1: Data collection

Collected and save reddit data using the reddit API (through the praw library). This involved below steps

Step 1: Creating a reddit account

Step 2: Creating a reddit app

Step 3: Scraping some reddit data

We were able to gain the understanding of about our data and the API such as how many API calls are required to collect the submissions .Submission time limit etc.

## Part 2 - Analyzing an existing dataset

We conducted descriptive analyses, via manipulation of data stored in a pandas dataframe, and via the creation and exploration of graphs, of the number of upvotes of reddit comments. This involved below steps.

Part 2.1 - Quick Descriptive Analyses

Part 2.2 - Plotting and the like

Part 2.3 Data Cleaning and some final regression-oriented data exploration

We learned some things about what predicts upvotes: Which subreddit the post is in is seems to matter quite a bit for the number of upvotes etc .

## Part 3 - Linear Regression

Conducted a linear regression to help understand the factors associated with a top post having many upvotes on reddit. Implemented additional feature sets and/or a new model and describe why those decisions were made and what their effects were on performance. This involved below steps

Part 3.1 - Regression to predict ups

Part 3.2 - Exploration of regression coefficients

Part 3.3 -Attempting to Improve our Predictions in future

We were able to find the strongest positive and negative predictor of upvotes. Additionally, we improved our RMSE by using Random Forest.
