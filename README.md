# Handwritten-character-recognition-using-the-Bay-s-classifier
Bay’s classifier is a classifier that minimizes a certain probabilistic 
error measure. The bay’s error is then the error of bay’s classifier. 
Bay’s classifier Performs probabilistic prediction and it is based on Bayes’ 
Theorem. In many of the applications, the relationship between the attributes
set and the class variable is non-deterministic. The notions of Bayes 
optimality and Bayes error generalize directly also to regression, but 
for simplicity we consider only classification here. A Bayesian classifier 
is based on the idea that the role of a (natural) class is to predict the 
values of features for members of that class. Examples are grouped in classes 
because they have common values for the features. Such classes are often 
called natural kinds. The idea behind a Bayesian classifier is that, if an 
agent knows the class, it can predict the values of the other features. 
If it does not know the class, Bayes' rule can be used to predict the class 
given (some of) the feature values. In a Bayesian classifier, the learning 
agent builds a probabilistic model of the features and uses that model to 
predict the classification of a new example. The simplest case is the naive 
Bayesian classifier, which makes the independence assumption that the input 
features are conditionally independent of each other given the classification.
The independence of the naive Bayesian classifier is embodied in a particular 
belief network where the features are the nodes, the target variable 
(the classification) has no parents, and the classification is the only 
parent of each input feature. The Optimal Bayes classifier maximizes the 
performance measure e(ˆf). We always use Bayes classifier as a benchmark
to compare the performance of all other classifiers
