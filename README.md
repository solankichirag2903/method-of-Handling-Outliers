Outliers :- Data points that significantly differ from other observations in dataset, These Datapoint are beyound range .
There are various method to handle outlier from our dataset.
steps to handle outliers are as follows: 
1) Boxplot using seaborn lib
2) Distplot using seaborn lib.
  a) After Distplot We understand which method perfectly shooted to handle outlier.
  b) If our distplot is skewed then we used IQR(Inter Quartile Range).
  c) Else when our dataset is normally we used Z-score method.
3) Method to Detected Outliers :
   a) Z-score Method
   b) Inter Quartile Range.
   c) Percentile Method.
   d) Winsorization.
   e) Finding Boundaries method.
4) Methods to handle Detected Outliers:
   a) Trimming Method : In these we totally remove all the outliers from our dataset
   b) Capping Method : In Capping we Basically squeezed the outliers in upper & lower bound
     i.e, when ever any outlier found it squeezed under the range of upper or loower limit or equal to that limits . Through these we deal with Outliers without removing any data from our dataset.
5) Models which are affected by Outliers are:
   a) Linear Regression
   b) Logistic Regression
   c) KNN
   d) Naive Bayes Classifier
   e) K-mean
6) Model Doesn't get Affected by Outliers :
   a) Decision Tree Algorithm
   b) Random Forest
   c) Support Vector Machine
   d) Neural Networks
7) Model Where Outlier are main Focuses are : Anamoly Detection 
