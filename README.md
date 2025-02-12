### Entity-Level Sentiment Analysis on Twitter

#### 1. Project Overview
In today's digital world, Twitter plays a key role in shaping public opinion and brand perception. This project develops an entity-level sentiment analysis model to classify tweets as Positive, Negative, Neutral, or Irrelevant regarding a specific entity (e.g., brands, products, public figures). The goal is to help businesses extract actionable insights, track sentiment trends, and enhance decision-making.

#### 2. Problem Statement
Traditional sentiment analysis focuses on entire texts rather than specific entities within them. This project bridges that gap by building a model that identifies sentiment at the entity level, providing more precise insights for businesses.

#### 3. Objectives
The aim of this project is to build a model that will be able to accurately classify tweets at the entity level into Positive, Negative, Neutral, or Irrelevant sentiments. This will help businesses and organizations to:
* Improve brand and reputation management
* Enhance customer engagement strategies
* Enable data-driven decision-making
  
#### 4. Target Audience
* Businesses & brands
* Marketing & PR teams
* Customer support teams
* Investors & analysts
  
#### 5. Data & Preprocessing
* Dataset sourced from [Kaggle.](https://www.kaggle.com/datasets/jp797498e/twitter-entity-sentiment-analysis)

#### 6. Data Understanding
Both the training and validation datasets had column names that did not make sense. The column names were renamed as below:
1. ID
2. Topic
3. Sentiment
4. Tweet
* The training dataset had 74681 rows and 4 columns while the validation dataset had 999 rows and 4 columns
* The training dataset had 686 missing values in the tweet column while the validation dataset had no missing values
* Both datasets had one column with integer data type and 3 columns with categorical data type

#### 7. Data Preprocessing
Preprocessing steps: text cleaning, stopword removal, lemmatization, tokenization, and label encoding.
  
#### 6. Modeling & Evaluation
Built two models:
* Logistic Regression Model (Baseline)
* Random Forest Classifier
Models Evaluated models based on accuracy score

#### 7. Findings & Conclusion
* The Logistic regression moidel had an accuracy score of 90%
The model with the highest accuracy ensures reliable entity-level sentiment classification, enabling businesses to monitor sentiment trends, improve customer experience, and strengthen brand perception.
