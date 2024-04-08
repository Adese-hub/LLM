# LLM Project

## Project Task

In this Language Model (LLM) project, I employed machine learning techniques to analyze and predict customer satisfaction ratings from review texts. The project is essentially a text classification challenge where the objective is to predict categorical ratings using Natural Language Processing (NLP) on customer feedback data. The goal of this is to improve business process, be able to accurtaely dertmine customer satisfcation, understand the gaps and customer training needed to be deployed to staff members 


## Dataset
The dataset chosen is from a 'singapore_airlines_reviews sourced from Kaggle. This dataset contains customer reviews and ratings for Singapore Airlines. The dataset is preprocessed; including filtering non-English text, tokenization, removing stopwords, and lemmatization. 


## Pre-trained Model
The project was done using logistic regression model, commonly used for classification tasks. This model was chosen for its efficiency and interpretability in text classification tasks.


## Hyperparameters
Hyperparameter tuning was done to enhance the model's predictive power. I employed GridSearchCV to methodically iterate over a range of hyperparameters and identify the optimal combination. The primary hyperparameters fine-tuned included the regularization strength 'C' and 'max_iter', which influences the convergence of the logistic regression algorithm.

## Business and Data Understanding 

The insights from this model facilitate precise enhancements in service provision. This proves especially valuable considering that customers who appeared dissatisfied in their textual reviews still gave ratings ranging from 3 to 5. Therefore, the model serves as a tool to uncover the genuine or adjusted ratings based on textual reviews.Specific terms like "legroom," "food quality," and "staff service" are closely linked to customer ratings. Higher ratings often mention positive experiences with "spacious legroom" and "attentive staff."
Utilized logistic regression to identify predictive factors of customer ratings.
Achieved model accuracy of 66.05%, reflecting a good predictive power from review texts.
Identified factors influencing passenger satisfaction include service quality, booking process, perceived attitude from staff,  and in-flight amenities.
The logistic regression model was optimized through hyperparameter tuning, with 'C': 1 and 'max_iter': 1000 as best parameters.
Deep data analysis combined with industry knowledge offers Singapore Airlines a strategic edge in enhancing customer satisfaction.
Insights from the model guide data-informed decisions for service improvement.
Supports initiatives for better customer experiences, satisfaction, and loyalty.

