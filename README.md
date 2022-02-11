# driving_behavior
AI tachometer is able to detect abnormal driving behavior with over 0.9999 prediction accuracy in real time.

# Python source programs
rfcv.py with 493 trees and entropy criterion is a Python program for 10-fold cross-validation using 24_27rand.csv.

rfcvgini.py with 493 and Gini impurity criterion is a Python program for 10-fold cross-validation using 24_27rand.csv.

evalcross.py is a 10-fold cross-validation Python program that runs rfcross.py 100 times, randomly generating the number of trees ranging from 150 to 500.

rfcross.py is a Python program that specifies the dataset file and the number of trees in a in random forest binary classification.

# datasets
24_27rand.csv can be used for this experiment.
It will be available on the request.

# results
Entropy:
10-fold cross-validation with random forest binary classification of 493 trees and entropy criterion was: [0.99993464 0.99993464 0.99991285 0.99986928 0.99993464 0.99989107 0.99995643 0.99993464 0.99989107 0.99989107]. The average accuracy is 0.999915 and the standard deviation is 0.000027.

10-fold cross-validation with random forest binary classification of 493 trees and Gini impurity:
with Gini impurity was calculated: [0.99993464 0.99986928 0.99989107 0.99984749 0.99993464 0.99989107 0.99995643 0.99993464 0.99982571 0.99984749]. The average accuracy with Gini impurity criterion is 0.999893 and the standard deviation is 0.000043. 


evalcross150_500.result

evalcross150_2000.result


