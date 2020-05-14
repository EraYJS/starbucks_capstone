# Starbucks Challenge

  Capstone Project of Udacity Data Scientist NanoDegree 

For a more detailed description, please checkout [medium blog](https://medium.com/@orange.ariza/how-to-encourage-people-to-toss-more-coins-to-their-coffee-1877c9efa6b5) for the project.

## Targets

This project have the following targets.

* find out the most influencial factors on customers' decision in accepting offers

* fit a model that predicts the best offers to send to a customer

## Conclusion

1. Most Influencial Factors
  For this target, I implemented Principal Component Analysis(PCA) to decompose the feature matrix, and named income and age as the most influencial factors.

2. Predicts Best Offers
  For this task, I implemented two models, a XGBoost and a Random Forest multi-output classifier, they are both fine-tuned via grid search to predict best offer to a customer.
  
## After Thoughts

For this project, in my opinion, the most important part is pre-processing and data re-organization. The project is well designed in terms of a data science practice. In addition, it's also a good reminder for me in future works.

**Take Away:**

* For supervised learning, labels should make good sense to people, before preceeding to machines

* Always try to develop better understanding of the business, before cleaning and preprocessing the data

