# Loan-Prediction Project

This project will help predict people with a high probability of paying you back their loans.

#### Data Source

The data set is publicly available from LendingClub.com. Lending Club connects people who need money (borrowers) with people who have money (investors). We will use lending data from 2007-2010.

#### Project Summary

We will create a model that will help predict people with a high probability of paying you back their loans.

![](/purpose.png)

The goal is to classify and predict whether or not the borrower paid back their loan in full.

#### Model Building

We perform the split of train and test data.Then, we build the ensemble model

#### Model Evaluation and Prediction

we build the model and train it with the train data and predict with the test data. In the Test data we get the accuracy of 84%.
![](/heatmap_of_accuracy.png)

#### Hyper-Parameter Optimization

Then we perform the hyper-parameter optimization but it doesnot affect the accuracy of the model

#### Conclusion

Random forest performed better than a single decision tree when it comes to 'not.fully.paid = 0' class; on the other hand, it actually performed worst for the other class. These final results can be improved by using further data cleaning techniques to solve the huge imbalance in our dataset.

Final Accuracy : 84%
