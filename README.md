# Linear-Classifier

Linear Classifier with different approaches to select data to train. 
Our goal is to find only "important" data to train. 

Classifier_Sample_Selection  
Method 1. Take the data that has higher loss to train. 

Method 2. Take the data that are further from SVM to train. 

Classifier_Linear_programming  
Method 3. Using Linear programming to find the data to train. 

Method 4. Using Integer Linear programming to find the data to train.



Conclusion:  
Sample selection methods obtained much better results than those obtained by choosing examples at random, proving that we can obtain good performances in classification while saving execution time and relying on a smaller number of examples.  

Results based on LP and ILP methods are even better: an expected result since these methods have access to the whole set of examples, and thus allows us to make more informed choices of examples and select less samples while achieving a better classification accuracy.
