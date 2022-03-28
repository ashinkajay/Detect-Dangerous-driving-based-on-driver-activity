# Driver-Distraction-Detection-Mini-Project-2022
A computer vision project to detect activities that generally compromise safety of the driver during driving. Here we use a computer vision model which monitors the activity of a driver during driving and classifies it as dangerous driving or not.Here we basically consider images of drivers where we check for various activities like movement of drivers, check whether eyes are closed  or usage of other objects like mobiles during driving. It uses a combination of features to detect dangerous driving such as :
1) Pixel Velocity
2) Edge
3) Colour Intensity
4) Height and Width of Face
5) Eye area
6) Face Region
7) Mouth Region
8) Tea Cup
9) Mobile Phone

The dataset consists of 100 images for each class with us having 10 classes, so a total of 1000 images for training, 100 images for validation and 100 images for testing purpose.

Here we classify it as dangerous driving based on certain classes:
1) Texting on the phone.
2) Talking on the phone.
3) Operating dashboard radio.
4) Drinking beverages.
5) Reaching behind across the seat.
6) Hair and Makeup application.
7) Talking to co-passengers with face not facing the road.
8) Bending down to adjust seat or pick up something from floor.
9) Safe driving

Algorithms used for Object Detection (Here we need to do object detection to identify mobile phones, cofee cups etc.):
1) YOLO
2) HOG
3) SSD
4) Spatial Pyramid Apooling

Evaluation Metrics used:
1) Mean Average Precision
2) Precision
3) Recall


Software Used:
Tensorflow keras, Opencv.

Hardware Used:
NVidia Jetson COMs
