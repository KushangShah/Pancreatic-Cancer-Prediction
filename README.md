# Pancreatic Cancer Prediction
 
 Doing self project on cancer prediction.

 # Conclusion

The accurancy of model is 87% which is amezing but, this results are misleading because most of the data belong to class 0 (No cancer). So if the model predict "class 0" for everyone, It will still achieve 87% score.

So when my model select 87%, it's for class 0. Which is correct most of the time.

for class 1:- <br>
0.00 to 0.08 score meaning model is predicting "Cancer" for only 8%(due to less data in dataset). Which makes the model wrong.<br>
Recall = 1. means that model never correctly predicts a cancer case.<br>
F1-score = 0.00 for class 1. confirms  that the model is useless for predicting cancer cases.<br>

<h3>Why this happen?</h3>
- 8730 (No Cancer) vs. 1270 (Cancer) <br>
- ~87% of the dataset is No Cancer.<br>
The models are biased toward predicting the majority class (0).

This could have been an amezing ML but since the dataset is imbalanced meaning, there is no particular path that leads to dead or lived, In medical everything is related to one another which could cause disease. 