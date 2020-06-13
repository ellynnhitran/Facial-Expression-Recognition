# Facial-Expression-Recognition
#Deep Learning, CNN, Keras, Tensorflow, Emotion Neuroscience. 


```
Challenges in Representation Learning: Facial Expression Recognition Challenge (From Kaggle)
```

```
Solution: Categorize each face based on the emotion shown in the facial expression in to one of 
seven categories (0=Angry, 1=Disgust, 2=Fear, 3=Happy, 4=Sad, 5=Surprise, 6=Neutral).
```
This script runs using Python 3. 


## Dataset
```
FER2013: 48 Features, 7 Labels, 35887 Examples.
```

## Data Pre-Processing
- Get features for training using numpy.
- Get labels for training using pandas. 
- Store them using numpy.
- Split data into training, testing and validation dataset.
- Save test samples to be used later. 

## Build model
- Design the CNN. 
- Complile model with adam optimixer and categorical crossentropy loss.

## Train model
- Calculate training and validation loss & accuracy (10 epochs).
- Calculate test loss & accuracy (101 data).

## Evaluate model
- Make prediction for custom image out of test set

![Mark Zukerberg](https://github.com/ellynnhitran/Facial-Expression-Recognition/blob/master/result%20mark%20test.png)



*Reference:
- Dataset from Kaggle: https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/data
- https://medium.com/themlblog/how-to-do-facial-emotion-recognition-using-a-cnn-b7bbae79cd8f
- https://sefiks.com/2018/01/01/facial-expression-recognition-with-keras/
