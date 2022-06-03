# **Project Description:Customer Feedback Sentiment Analysis & Prediction**
 
# **Data Description**:

- A sentiment analysis job about the customer feedback
- Feedback talks about different IT Services, Infrastructure etc.

# **Dataset**:

- Contains two columns "review" & "label"
    - review : Customer Feedback about the Product and the Service
    - label : '1' for Negative and '0' for Positive

# **Objective**:

- To classify the sentiment of customer reviews into the positive or negative, with negative sentiments being in focus

# **Steps Applied**:
- Text based EDA
# WordTag Cloud
- Basic understanding of text pre-processing.
# Data Pre-processing:
- Remove html tags.
- Replace contractions in string. (e.g. replace I'm --> I am) and so on.\
- Remove numbers.
- Tokenization
- To remove Stopwords.
- Lemmatized data
- We have used NLTK library to tokenize words , remove stopwords and lemmatize the remaining words.

- What to do after text pre-processing:
    - Bag of words
    - Tf-idf
- Modeling Criteria
### Model evaluation criterion

### Model can make wrong predictions as:

1. Predicting a Review/Feedback being Negative, but in reality it is Positive. 
2. Predicting a Review/Feednack being Positive, but in actuality it is Negative

### Which case is more important? 
* Both the cases are important as:

* If a positive Feedback is termed as Negative, it's a lot of resource. False Positive

* If a Negative Feedback is termed as Positive, it's a lot of opportunity which in turn will result high Churn Rate. False Negative 



### How to reduce the losses?

* Product would want `F1 Score` to be maximized, greater the F1  score higher are the chances of minimizing False Negatives and False Positives. 
- Build the classification model.
    - Traditional Supervised Approach
    - Transfer Learning Methods
    - Fine Tuning Transfer Learning

- Tune & Evaluate the Model performance.
