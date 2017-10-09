****Documentation in Progress

In this project, I tried to understand how anomalies can be handled in classifying TextMessages. There is a strong difference between finding anomalies in text corpus and find "text message anaomalies"

Example: Text Message Anomalies - Classifying anomalies in Twitteer Corpus

Difference between classification and anomaly detection:
     In classification, one can find class-balanced dataset, where as in anomaly detection, the ration of classes is imbalanced (typically 1000:5)
     
Dataset:
   Because I could not find such anomaly twitter corpus, I have made an anomaly dataset changing the ration of positive:negative samples to 4000:20 using the original dataset(balanced class ratio) 

References:
1) Working with text data scikit-learn
http://scikit-learn.org/stable/tutorial/text_analytics/working_with_text_data.html
2) Supervised outlier detection
https://link.springer.com/content/pdf/10.1007%2F978-1-4614-6396-2_6.pdf
3) How to handle outliers in text data
https://link.springer.com/content/pdf/10.1007/978-1-4614-6396-2_7.pdf
