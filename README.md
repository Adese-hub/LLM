# LLM Project

## Project Task
This LLM project involves using machine learning to understand and predict patterns based on text data. This is a classification task where we are trying to predict rating categories based on text reviews.


## Dataset
The dataset chosen is from a 'singapore_airlines_reviews sourced from Kaggle. This dataset contains customer reviews and ratings for Singapore Airlines. The dataset is preprocessed; including filtering non-English text, tokenization, removing stopwords, and lemmatization. 


## Pre-trained Model
The pre-trained model selected is 'bert-base-uncased'. BERT (Bidirectional Encoder Representations from Transformers) model pre-trained on a large corpus of English data in an unsupervised manner. BERT models are typically designed to understand the context of a word in a sentence by considering the words that come before and after it.


## Performance Metrics
To evaluate the performance of my model, I am using accuracy and average loss. Accuracy measures the proportion of correct predictions over the total number of predictions, and the average loss was calculated to understand how close the model's predictions are to the actual labels, on average.


## Hyperparameters
The hyperparameters getting tuned are learning rate and batch size. 
I tried learning rates of 1e-5, 2e-5, and 3e-5, which are small values typical for fine-tuning tasks to ensure the pre-trained weights are not drastically altered.
I also tried batch sizes 16, 32, and 64, which are common sizes that balance the trade-off between the computational efficiency and the stability of the learning process.
After the hyperparameter tunning an accuracy of 1 is derived. Although this might seem ideal - it is most unlikely to get a perfect score. This might be due to an unforeseen data leakage or the small size of the data used. Caution will be taken in the future to prevent this challenge.  


