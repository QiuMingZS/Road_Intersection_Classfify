# Road_Intersection_Classfify
Using CNN to classify road intersections, including datasets prepare and image operation

* TensorFlow Version: 1.12.0
> Author: To_Fourier, CiWei. Maybe as you guessed, To_Fourier is another name of QiuMingZS. 

## 1.Project Description:
This project is designed for classification of 9 road intersections. As you know, there are many directions of an intersection and the view is quite different. Thus, according to the type of intersections, we devide each intersection into several child-class in order to improve the classification accuracy.

## 2.File Description:
Network.py:           design of our cnn network

datasets_prepare.py:  help you to build your own datasets

image_pre_process.py: make images ready to be send to the network

train.py:             train the designed network

test.py:              get the result of road intersection classification

## 3.Network Description
image -> conv1 -> pool1 -> conv2 -> pool2 -> conv3 -> pool3 -> fc1 -> fc2 -> fc3 -> softmax -> class

## 4.Functions:
Pool: max_pool

Activate: ReLU

## 5.Written at the end:
If you have any questions, welcome to raise an issue!
