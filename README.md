# CozmoGestureRegonize
using 3DCNN model by Keras to recognize four type gestures, and then perform related actions

### Training pics 
* Download from https://twentybn.com/datasets/jester. Every video in this data set is a collection of 38 pics captured from the related gesture video

### About Training
* When I using the Adadelta optimizer, I got 99% acc at the 20th epoch. This can't be achived when i using default Adam optimizer which ends up with 30% acc at last. So i recommand Adadelta optimizer strongly. 
* By the way, SGD optimizer performs almost the same acc result as Adam optimizer in this data set with my computer with 50 epochs and 1500 train videos per epoch.

### Result Recently
* Result video in Youtube https://www.youtube.com/watch?v=g0NhbYyRPEo .
* Cozmo can read out your gesture and action based on it. 
