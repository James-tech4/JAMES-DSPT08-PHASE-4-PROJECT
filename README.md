## BUILDING AN NLP MODEL FOR ENTITY-LEVEL SENTIMENT ANALYSIS ON TWITTER

* Student Name: JAMES WACHIRA MUTHEE
* Mode of Study: PART TIME
* Project: End of Phase Project
* Technical Mentor: Daniel Ekale

#### 1. Project Overview
In today's digital world, twitter plays a key role in shaping public opinion and brand perception. This project develops an entity-level sentiment analysis model to classify tweets as Positive, Negative, Neutral, or Irrelevant regarding a specific entity (e.g., brands, products, public figures). The goal is to help businesses extract actionable insights, track sentiment trends, and enhance decision-making.

#### 2. Problem Statement
Traditional sentiment analysis focuses on entire texts rather than specific entities within them. This project bridges that gap by building a model that identifies sentiment at the entity level, providing more precise insights for businesses.

#### 3. Objectives
The aim of this project is to build a model that will be able to accurately classify tweets at the entity level into Positive, Negative, Neutral, or Irrelevant sentiments. This will help businesses and organizations to:
* Improve brand and reputation management
* Enhance customer engagement strategies
* Enable data-driven decision-making
  
#### 4. Target Audience
The target audience for this project are:
* Businesses & brands
* Marketing & PR teams
* Customer support teams
* Investors & analysts
  
#### 5. Data
* Dataset sourced from [Kaggle.](https://www.kaggle.com/datasets/jp797498e/twitter-entity-sentiment-analysis)

#### 6. Data Understanding
Both the training and validation datasets had column names that did not make sense. The column names were renamed as below:
1. ID-A unique identifier for each tweet.
2. Entity-The topic being discussed in the tweet.
3. Sentiment-The emotion assigned to the tweet
4. Tweet - The actual text of the tweet
* The training dataset had 74681 rows and 4 columns while the validation dataset had 999 rows and 4 columns
* The training dataset had 686 missing values in the tweet column while the validation dataset had no missing values
* Both datasets had one column with integer data type and 3 columns with categorical data type

#### 7. Exploratory Data Analysis
Some visualizations were done on the training data to get some deeper insights on it's distribution.

#### 8. Data Preprocessing
Preprocessing steps applied are:
* Stopword removal
* Lemmatization
* Tokenization
* Label encoding.
  
#### 9. Modeling & Evaluation
Built two models:
* Logistic Regression Model (Baseline)
* Random Forest Classifier
* Models were Evaluated models based on accuracy score

#### 10. Validating the Model
The best model was validated using validation data 

#### 11. Findings & Conclusion
* Logistic regression model had an accuracy score of 76%
* Tuned Random Forest Model had an accuracy score of 89.6%
  
The tuned Random Forest Model was therefore considered the best for this sentiment analysis project due to the high accuracy score. It generalized well to the validation dataset. 
