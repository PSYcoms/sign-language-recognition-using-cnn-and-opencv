# sign-language-recognition-using-cnn-and-opencv

# ABSTRACT
Sign language is one of the oldest and most natural form of language for communication. Since most people do not know sign language and interpreters are very difficult to come by, we have come up with a real time method using neural networks for detecting sign language. Our method detects hand gestures and predicts the sign language and gives the corresponding English alphabet.
To provide an easy immersive augmented experience which is also gesture enabled, we employ a web camera which is integrated with OpenCV libraries through a compiler.
With the advent of Artificial Neural Networks and Deep Learning, it is now possible to build a system that can recognize objects or even objects of various categories (like red vs green apple). Utilizing this, here we have an application that uses a deep learning model trained on the ASL Dataset to predict the sign from the sign language given an input image or frame from a video feed. 
In this method, the hand is first passed through a filter and after the filter is applied the hand is passed through a classifier which predicts the class of the hand gestures. This method provides 96.43 % accuracy for the 26 letters of the alphabet.

## OBJECTIVE
To make a sign language detector which can detect English alphabets through hand gestures.
To recognize objects using ANN and Deep learning.
To capture frames from videofeed using opencv.
To predict sign captured with a confidence level greater than 20%. If sign is predicted with a low confidence level i.e. between 20%-50% it is presented with a maybe sign, if it is with a high confidence level i.e. above 50% it is presented in blue colour with confidence percentage.


