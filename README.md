**Problem Statement**
Data includes airline reviews from 2006 to 2019 for popular airlines around the world withmultiple choice and free text questions. 
Data is scraped in Spring 2019. The main objectiveis to predict whether passengers will refer the airline to their friends.

**Project Summary**

In this project ,we shall be doing analysis to find whether a passengeer will recommend the airline to their friend.We shall be going through data and rating given by passenger on various aspects of service like,seatcomfort,cabin service,ground service, value for money and other.

We shall start our project by importing important libraries.Once done we shall start cleaning our data.We shall dropping certain columns and deleting some duplicate rows too. Then we shall use graphical or non graphical method for EDA before handling null values,because the count of null value is high so we shall have to drop them.We shall draw certain conclusion on the basis of it.Once we have drawn our conclusion we shall be handling null values and imputing them as required.

We shall be using heatmaps to find correlations bteween variable and then drawing some conclusions on that basis. We shall we removing multicollineraty.

Once done we shall be splitting our data in dependable variables(Y) and independentable variables(X). Then our data into test and train data.

We shall be implementing following models:

Logistic Regression:What is meant by logistic regression? Logistic regression is a data analysis technique that uses mathematics to find the relationships between two data factors. It then uses this relationship to predict the value of one of those factors based on the other. The prediction usually has a finite number of outcomes, like yes or no. Once done I had used Confusion Matrix and then impelmenting cross validation

Decision Tree: A decision tree algorithm is a machine learning algorithm that uses a decision tree to make predictions. It follows a tree-like model of decisions and their possible consequences. The algorithm works by recursively splitting the data into subsets based on the most significant feature at each node of the tree. Then HYPERPARAMETER TUNING is done.

Random Forest:The random forest takes the prediction from each tree and based on the majority votes of predictions, and it predicts the final output. The greater number of trees in the forest leads to higher accuracy and prevents the problem of overfitting.After implementing Random Forest cross validation is done.

K-nearest Neighbour:A k-nearest-neighbor algorithm, often abbreviated k-nn, is an approach to data classification that estimates how likely a data point is to be a member of one group or the other depending on what group the data points nearest to it are in.The k-nearest-neighbor is an example of a “lazy learner” algorithm, meaning that it does not build a model using the training set until a query of the data set is performed.

Support Vector Machine:A support vector machine (SVM) is a type of deep learning algorithm that performs supervised learning for classification or regression of data groups.

Naive Bayes Classification:The Naïve Bayes classifier is a supervised machine learning algorithm, which is used for classification tasks, like text classification. It is also part of a family of generative learning algorithms, meaning that it seeks to model the distribution of inputs of a given class or category.

Then I created the function to compare the scores.Thereafter conclusion has been drawn.

**Conclusion:**

The Models used for this Classsification problem are

Logistic Regression Model
Decision Tree Model
Random Forest Model
K-Nearest Neighbor Model
Support Vector Machine Model 6.Naive Bayes
We performed Hyperparameter tuning using Gridsearch CV method for Decision Tree Model, Random Forest Model , K-Nearest Neighbor ,Support Vector Machine and Naive Bayes. To increase accuracy and avoid Overfitting Criteria, this is done. After that, we finalized the Gradient Boosting model by fine-tuning the hyperparameters.

Based on the knowledge of the business and the problem usecase. The Classification metrics of Recall is given first priority , Accuray is given second priority , and ROC AUC is given third priority.

We have built classifier models using 6 different types of classifiers and all these are able to give accuracy of more than 90%.

Recall score of Support Vector Machine is highest.

The most important feature are overall rating and Value for money that contribute to a model's prediction whether a passenger will recommened a particular airline to his/her friends.

The classifier models developed can be used to predict passenger referral as it will give airlines ability to identify impactful passengers who can help in bringing more revenues.
As a result, in order to increase their business or grow, our client must provide excellent cabin service, ground service, food beverage entertainment, and seat comfort.
