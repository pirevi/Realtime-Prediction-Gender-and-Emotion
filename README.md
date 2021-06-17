# Realtime Prediction for Gender and Emotion (Keras, TensorFlow, OpenCV)
### Goal: 
To create a Convolutional Neural Network based model which will be able to identify the gender and emotion of a person in real time.

### Description: 
For achieving our goal, we need to create two separate models. One which will be trained to classify faces based on gender and the other one which will be able to detect emotion of the face. Both these models will be combined to give a real-time detection and prediction of gender and emotion. We have used Tensorflow with Keras for our model training and OpenCV for real-time face detection and prediction. 

### Dataset Information:
As we need to create two models, One for gender and the other for emotion. We required two datasets. The data set chosen for this was FER-2013 for Emotion prediction and UTK-Face Dataset for gender prediction.
  
#### [FOR MORE INFORMATION, GO THROUGH THE ATTACHED PDF]

#### NOTE: The model files (which contain the architecture and weights) is not uploaded here. It is due to upload file size limitaion on github(25MB). Only the code files are present, which when trained on the dataset can reproduce the model files.

<img src="/imgs/expressions.png" alt="Emotion Detection"/>
<img src="/imgs/male_female.png" alt="Gender Detection"/>
