# TASK3NLP
I Have used A NAIVE BAYES CLASSIFIER to do nlp task and classify the data in the dataset into its product category using the description column only.
Naive Bayes algorithm is a simple classification machine learning /natural language  algorithm which uses probability of the events for its goal. It is based on the Bayes Theorem pf probability which assumes that there is no interdependence amongst the variables.Thus Calculating these probabilities will help us calculate probabilities of the words in the text. AND MAKING THEIR VECTOR to know how much time a word comes up .
For cleaning the data , i have used NLTK library and RE library in python which allows to ignore all stopwords such as articles , this, of etc. and re for editing the words with the help of regular expressions.
For training the model , i have used the most popular library that is scikit learn and module of naive bayes from it and for accuracy check , i have make confusion matrix with help of metrics module of scikit learn library.

#What ideas do you have to improve the accuracy of the model? What other algorithms would you try?
We can use other natural language processing algorithms to check the accuracy of each algorithms on the dataset given such as logistic regression,CART which is a model based on decision trees, Maximum Entropy again related to Decision Trees, Hidden Markov Models which are models based on Markov processes.
