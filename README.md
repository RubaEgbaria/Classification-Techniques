# Classification Techniques 

# Part One:  

In this Assignment you will explore and experiment with several classification and predictive modeling (KNN, 

SVM, Decision tree and Naïve Bayesian). 

For decision tree you should tune it for the best hyperparameters  

For KNN you should tune it for best K 

For the best tuned classifier, you should determine the 

• The confusion matrix 

• Precision 

• Recall 

• F1-Score 

• Draw the ROC curves for all classifier on one graph 

Interpret and explain your observation on result 

# Part Two: 

Draw the training error and validation error curves on one graph for each of the above algorithm as follows 

A. First split your data into training set 70% and test set 30% 

B. Use cross validation technique on train set to draw the training and validation error as follows 

• Repeat the experiment 10 times, in first experiment use 10% of the training set for training and 
validation, in the second experiment used 20% of training set for training and validation and so on 
until the tenth experiment were use 100% of training set for training and validation. 

• In each experiment divide the used set (i.e. the 10% or 20% .. or 100% of training set) into 10 folds 
where one-fold used for validation and the other 9-folds used for training, in which it will repeated 
10 times each time record the training error and validation error and finally take the average for the 
training and validation 

• After finishing the 10 experiments you will have 10 average values for training error and 10 average 
values for validation error 

• Finally draw the training error curve and validation error curve with respect to training set size used 
in each experiment  

• Show if overfitting or underfitting are appear in your algorithm if so, solve it and show the result 
after you solve it 

• Compare the training error, validation error with test error for each algorithm algorithms 

_____________________________________________________________________________________________

Note 1. You can find the data file on Moodle course page as “globalterrorism” 

Note 2. The target column are the attack types 

Note 3. You need to pre-process the data such as filling missing, cleaning, scaling etc., you should do that 
before you start applying the algorithms 
