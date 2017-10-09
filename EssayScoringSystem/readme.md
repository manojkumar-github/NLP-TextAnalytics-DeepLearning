 ***Documentation in progress


Student Essay Scoring System:
 
 This is an automatic grading system which solves the issues of many teachers and can avoid human mistakes while grading students. This is my intial research and will periodically update my research and results over the next week of time.
 
 Current Status:
   As of now, I prepared a baseline model, where I used various regression techniques to score each essay. The performance is not bad but needs to be improved by finding best parameters or other deeper models. This can also be handled as a classification problem where Quadratic-Kappa Score can be used as a evaluation measure.
 

Dataset:
https://www.kaggle.com/c/asap-aes#description

Out of all columns in the dataset, we are going to deal with essay_set,essay,domain1_score
essay_set = each essay is categorized into 8 different essay sets with essay set names(1,2_1,2_2,3,4,5,6,7)

References:

http://www.cs.cmu.edu/~norii/pub/aes.pdf

References:
http://www.cs.cmu.edu/~norii/pub/aes.pdf
