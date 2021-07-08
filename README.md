# Text-Classification-ML
A working ML model to classify social media text to remove and report the text which is not suitable from the social media platform and thus control hate speech.

This project aims at classifying social media Hinglish text based on aggression into 3 classes namely NAG(Non Aggressive), CAG(Covertly Aggressive) and OAG (Overly Aggressive).

Covertly Aggressive (CAG): This label was given to comments which had a hint of hate speech or had some moderately bad words.
Overtly Aggressive (OAG): This label was given to comments which had conspicuous hate and had explicit abusive words.
Not Aggressive (NAG): The rest of the comments were labelled as non-aggressive

Methods	& Accuracies %
1.	SVM	- 74.31 %
2.	XGBoost	- 68.96 %
3.	Logistic Regression	- 71.13%
4.	BOW	- 66.73%
5.	BiLSTM	- 59.18%
6.	CNN	- 68.30%
