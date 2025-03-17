1) PROBLEM STATEMENT :
   
   . This project understands whether a person will accept the coupon recommended to him in different driving scenarios

2) DATA COLLECTION :

    . Data Source - https://archive.ics.uci.edu/dataset/603/in+vehicle+coupon+recommendation(Note:First login to UCI Machine Learning Respiratory)

    . The data consists of 25 columns and 12,684 rows

3) DATASET INFORMATION :
   
  . This data was collected via a survey on Amazon Mechanical Turk.

  . The survey describes different driving scenarios including the destination, current time, weather, passenger, etc., 
 and then ask the person whether they will accept the coupon if they are the driver.

  . For more information about the dataset, please refer to the paper:

  . Wang, Tong, Cynthia Rudin, Finale Doshi-Velez, Yimin Liu, Erica Klampfl, and Perry MacNeille.
  'A Bayesian framework for learning rule sets for interpretable classification.
  
  ' The Journal of Machine Learning Research 18, no. 1 (2017): 2357-2393.   

4)  SUMMARY

  . The dataset has 12,684 rows and 25 columns.

  . The target variable is "Y" (1: accepted coupon, 0: did not accept).

  . Most columns are categorical, while a few are numerical.

  . Some columns have missing values, especially "car" (only 108 non-null values).

  . Next Steps:

  1. Handle Missing Values (impute or drop).


  2. Encode Categorical Variables for classification models.


  3. Visualize Data for insights.


  4. Build and Evaluate Classification Models (e.g., Logistic Regression, Decision Tree Classifier, Random Forest Classifier, SVM Classifier,
                                             KNN Classifier ).  
