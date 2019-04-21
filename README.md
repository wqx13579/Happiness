# Happiness Project Proposal

## 1. *Team Members: Qingxu Wang, Zening Li*

## 2.*Problem and Motivation:*
### Fit the model of happiness related to region of the world, GDP per Capita, family wellness, health conditions, freedom and some other factors.

### The purpose of this study is to understand what are the main factors making people happy, so we can commit more energy on those main factors.

## 3. *Libraries and Tools needed:*
### Statistical testing, Cloud computing basics(AWS EC2, S3, IAM etc.). We need to learn the Stats model for linear regression, statsmodels and sklearn for logistic regression, and model evaluation and selection.

## 4. *Data Collection Details:*
Happiness Data for 2015,2016 and 2017 from Kaggle:

[https://www.kaggle.com/unsdsn/world-happiness#2015.csv](https://www.kaggle.com/unsdsn/world-happiness#2015.csv)

[https://www.kaggle.com/unsdsn/world-happiness#2016.csv](https://www.kaggle.com/unsdsn/world-happiness#2016.csv)

[https://www.kaggle.com/unsdsn/world-happiness#2017.csv](https://www.kaggle.com/unsdsn/world-happiness#2017.csv)

### variables:
Country: Name of the country.

Region: Region the country belongs to.

Happiness Rank: Rank of the country based on the Happiness Score.

Happiness Score: A metric measured in 2015 by asking the sampled people the question: "How would you rate your happiness on a scale of 0 to 10 where 10 is the happiest."

Standard Error: The standard error of the happiness score.

Economy (GDP per Capita): The extent to which GDP contributes to the calculation of the Happiness Score.

Family: The extent to which Family contributes to the calculation of the Happiness Score

Health (Life Expectancy): The extent to which Life expectancy contributed to the calculation of the Happiness Score

Freedom: The extent to which Freedom contributed to the calculation of the Happiness Score.

Trust (Government Corruption): The extent to which Perception of Corruption contributes to Happiness Score.

Generosity: The extent to which Generosity contributed to the calculation of the Happiness Score.

Dystopia Residual: The extent to which Dystopia Residual contributed to the calculation of the Happiness Score.

## 5. *Literature Review(if any):*
### There's none at this moment, we would append the articles here if we find it necesssary.

## 6. *Work before build model:*
### We need to clean up the data. The reason is that some attributes we do not need to use so we need to remove these data, and there might be missing values we need to handle.  We also need to create hypothesis, for example, is GDP per capital independent? Or is it related to health conditions? And then with these hypothesis, we can perform desired tests.  Data bias analysis is also a good approach to let us better do data cleaning.

## 7. *Predictive Task and model detail, model evaluation and selection strategy:*
### We want to use the existence data to predict the future result. We wish to use linear (or more complicated method if mentioned in later classes) regression to create the model. We want to find what is affect the happiness so we wish to use GDP per Capita, family wellness, health conditions, freedom and some other factors to predict which factor will affect the happiness more in the future.

## 8. *How to test the model:*
### Split the set into training set and testing set, create the model with training set and test the model using training set.  For AWS cloud, we're not familiar with AWS at this moment, we might be using AWS API for the project, unknown at this time.

## 9. *Timeline:*
Dataset and motivation Research Questions | 0 weeks
---|---
Data cleanup       |                        1 weeks
Modelling activity/evaluation and findings | 2 weeks
Statistical Summary            |            2 weeks
Main visualization             |            2 weeks  
