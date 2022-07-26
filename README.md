# Movie-Recommendation withh Naive Bayes

### Business Objective:
* Based on rating scores that users gave to movies they watched, we try to predict whether they will be like movies recommended or not.

### Load Data
* The data set include 610 users and 9724 movies

### Data Processing, Data Cleaning
* Rating distribution:

26.6% are of rataing 4, follow by 19% of rating 3, then 13% are of rating 5 and 3.5.

rating 0.5, 1, 1.5, 2, 2.5, and 4.5 count for 1.3%, 2.8%, 1.8%, 7.5%, 5.5%, and 8.5% respectively. 

* we will take the movie with most ratings as the target movie (outcome): Movie ID 356 has 329 ratings
* The ratings of the rest movies of users are predictors.
* We will construct the input dataset by removing variable movie_id 356 out of the data
* We can consider movies with rating greater than 3 as being liked (being recommended)

### Data Modeling
* We apply Naive Bayes model for movie recommendation

### Model Evaluation
* The model accuracy is:  81.8%
* Precision: 0.84
* Recall: 0.96
* f1 score; 0.9
* AUC score: 0.6

### Turn models with cross-validation
* AUC with the best model 0.56



