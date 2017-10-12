****Documentation in Progress

-- Refer to .ipynb notebook in this project for the code explained visually

In this project, I tried to understand how anomalies can be handled in classifying TextMessages. There is a strong difference between finding anomalies in text corpus and find "anaomalies among text message "

Example: 

1) Text Message Anomalies - Classifying anomalies in Twitteer Corpus
2) Classifying student essays as good/bad

Difference between classification and anomaly detection:
     In classification, one can find class-balanced dataset, where as in anomaly detection, the ration of classes is imbalanced (typically 1000:5)
     
Dataset:
   Because I could not find such anomaly twitter corpus, I have made an anomaly dataset changing the ration of positive:negative samples to 4000:20 using the original dataset(balanced class ratio). 
   
Techniques to deal with Anomaly Detection(Outliers Detection)

1) Cost-Sensitive Learning
     a) MetaCost: A Relabelling Appraoch
     b) Weighting Methods: Bayes Classifier, Proximity Based Classifiers, Rule-Based Classifiers, Decision Trees,SVM Classifier
2) Adaptive Resampling:
     a) Relationship between weighing and sampling
     b) Synthetic OverSampling (SMOTE)
     c) One Class Learning with Positive Class (Ex:OneClassSVM in scikit-learn)
     d) Ensemble techniques
3) Boosting Methods:
     
   
Out of all the state of the art-of-techniques, I have tried Cost-Sensitive Learning(adding more weights to the anomaly classes). This is
done solely for my understanding. I will work on this on a bigger dataset and try various techniques mentioned above.

Original Dataset:
https://www.kaggle.com/c/si650winter11#description

References:
1) Working with text data scikit-learn
http://scikit-learn.org/stable/tutorial/text_analytics/working_with_text_data.html
2) Supervised outlier detection
https://link.springer.com/content/pdf/10.1007%2F978-1-4614-6396-2_6.pdf
3) How to handle outliers in text data
https://link.springer.com/content/pdf/10.1007/978-1-4614-6396-2_7.pdf
