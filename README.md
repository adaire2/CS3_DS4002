# CS3_DS4002
# Restaurant Pricing and Consumer Perception: A Case Study
This repository contains background and reference material to get your started as well as the data and scripts required to complete the case study.




# How to Proceed Through the Study

## Step 1: Data  
Start by accessing the Yelp Open Data Set. You can find it here : 'DATA/Yelp-JSON.zip It includes user-generated ratings and business details. Then procees to the next step once you have accessed it.

## Step 2: Data Cleaning and Exploration  
Filter the dataset to include only restaurants in Philadelphia, PA with both price and review data. Clean the data by handling missing values, removing duplicates, and excluding non-restaurant entries. Use summary statistics and visualizations to explore rating and price distributions.  
Run this step using: `SCRIPTS/yelp_restaurant_cleaning.ipynb`

## Step 3: Sentiment Analysis  
Use the VADER sentiment tool to analyze customer reviews. Compute the average sentiment for each restaurant, then group and compare those averages by price level (1–4).  
Run this step using: `SCRIPTS/Project_1_Analysis_Plan.ipynb`

## Step 4: Statistical Testing  
Run an ANOVA to test whether sentiment scores differ significantly across price groups (p < 0.05). Then, perform a Spearman rank correlation to assess the strength and direction of the relationship between price and sentiment.  
ANOVA: `SCRIPTS/Project_1_Analysis_Plan.ipynb`  
Spearman correlation: `SCRIPTS/spearman_analysis.ipynb`

## Step 5: Draw Conclusions  
Interpret your results and summarize what the analysis reveals about the relationship between restaurant price and customer sentiment.


