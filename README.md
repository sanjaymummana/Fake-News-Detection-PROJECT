# Fake-News-Detection-PROJECT
Fake news detection using Data Analytics method along with python language.  
The dataset used for this project is train.csv. Dataset has a shape of (20800*5). The dataset has five columns: first identifies the news id, second and third are title and author and the fourth one is the text and finally the fifth one denoting FAKE or REAL.  
Follow the below steps to complete the project:  
1)Importing the Dependencies.  
a) printing the stopwords in English  
2)Data Pre-processing.  
a) loading the dataset to a pandas DataFrame  
b) counting the number of missing values in the dataset  
c) replacing the null values with empty string  
d) merging the author name and news title  
e) separating the data & label  
3)Stemming.  
a)separating the data and label  
b) converting the textual data to numerical data(TfidfVectorizer())  
4)Split the dataset into training and testing models.  
5)Training the Model: Logistic Regression.  
6)Evaluation.  
a) accuracy score on the training data  
b) accuracy score on the test data  
7)Making a Predictive System  
8)After completion of the project, we get an accuracy of 97.9%.  
Software requirements: Google colab.  
Programming Languages and modules: Python3, Numpy-module, pandas, sklearn.  
