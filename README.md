# Toxic - Comment - Challenge      

[캐글주소](https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge)     

​       

<br/>

--------------

### Data description

Provided with a large number of Wikipedia comments which have been labeled by human raters for toxic behavior. The types of toxicity are:

- `toxic`
- `severe_toxic`
- `obscene`
- `threat`
- `insult`
- `identity_hate`

​         

__Create a model which predicts a probability of each type of toxicity for each comment.__      

<br/>

----------

### File description

- **train.csv** - the training set, contains comments with their binary labels
- **test.csv** - the test set, you must predict the toxicity probabilities for these comments. To deter hand labeling, the test set contains some comments which are not included in scoring.
- **sample_submission.csv** - a sample submission file in the correct format
- **test_labels.csv** - labels for the test data; value of `-1` indicates it was not used for scoring;