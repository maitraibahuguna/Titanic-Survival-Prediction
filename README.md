# Problem Statement
Titanic Survival Prediction using Machine Learning

# Abstract
The Royal Mail Ship (RMS) Titanic known as unsinkable ship is the largest liner built in 1912, of the estimated 2224 passengers and crew aboard, more than 1500 died after the ship struck an iceberg during her maiden voyage from Southampton to New York City. However theie were certain people who survived. The one's who survived belonged to a particular class of society i.e. only rich and popular people were saved.<br>
In this project, we analyze the Titanic dataset set obtained from kaggle and will make two prediction. One prediction to see which passengers on board the ship would survive and then another prediction to see if we would have survived if were on board.<br>
After analyzing the dataset, it has been noticed that the passengers who purchased tickets of class A and with maximum fares survived the most. We have done visualization of each and every parameter to check the survival rate.<br>

# Data Description
Data Source: https://www.kaggle.com/c/titanic
The dataset collected from Kaggle  is the subset of original dataset consisting of has information about the passengers and crew which are P-class, name, age, sex, etc., and can be used to predict if the person onboard has survived or not.<br>
The data has been split into two sets : training dataset(80%) and test dataset(20%).The training set is used to build our
machine learning models. The training set includes our target variable, passenger survival status along with other independent features like gender, class, fare, and Pclass. The test set should be used to see how well our model performs on unseen data. The test set does not provide passengers survival status. We are going to use our model to predict passenger survival status. The test set should be used to see how well your
model performs on unseen data. For the test set, we do not provide the ground truth for each passenger. It is your job to predict these outcomes.
For each passenger in the test set, use the model we trained to predict whether or not they survived the sinking of the Titanic.<br>
We have used different machine learning models to make our predictions. The algorithms are: Logistic Regression algorithm, KNN algorithm, Support Vector Machine algorithm, Kernel SVM algorithm, Naive Bayes algorithm, Decision Tree algorithm and Random Forest algorithm. Confusion matrix is shown and accuracy for every algorithm is calculated. 

# Conclusion
We evaluated the performance of the model.On the train data the algorithm with best accuracy is Decision Tree with training accuracy of 99.29%.On the test data the algorithm with best accuracy is Random Forest with testing accuracy of 83.91%.<br>
As per the calculated test and train accuracy I have used Random Forest Algorithm to make prediction
for which passenger on board the ship would survive and then another prediction to see if i would have survived.After substituting the values,it looks like I would have not been survived.
