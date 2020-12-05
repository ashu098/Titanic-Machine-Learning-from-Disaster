Kaggle Competition

Titanic Competition - Analysis and Prediction

We have given information about the details of the passengers aboard the titanic and a column on survival of the passengers. Those who survived are represented as “1” while those who did not survive are represented as “0”. We have to determine if with the other features/information about the passengers it is possible to determine those who are likely to survive.

1. We have to preprocess given data in train.csv and test.csv file and include only those columns or feature vector which our model have to extract feature from gievn data

2. After preprocessing, we import our machine learning model which is Gaussian Naive Bayes classifier 

Brief about : Naive Bayes


Naive Bayes methods are a set of supervised learning algorithms based on applying Bayes’ theorem with the “naive” assumption of conditional independence between every pair of features given the value of the class variable. Bayes’ theorem states the following relationship, given class variable y and dependent feature vector x1 through xn :

P(y|x1,..,xn) = P(y) * P(x1,..,xn|y) / P(x1,..,xn)

Gaussian Naive Bayes : GaussianNB implements the Gaussian Naive Bayes algorithm for classification. The likelihood of the features is assumed to be Gaussian:

![alt text](https://miro.medium.com/max/1576/1*0If5Mey7FnW_RktMM5BkaQ.png)

3. train our model using gaussian naive bayes

4. predict survival value for given passenger id in terms of 0 or 1 whether person survive or not

5. In this model i have achieved 76.55% accuracy over test dataset
