# The-Autonomous-Vehicle

This code helps in getting the steering angle of self driving car. The inspiraion is taken from [Udacity Self driving car](https://github.com/udacity/CarND-Behavioral-Cloning-P3) module as well [End to End Learning for Self-Driving Cars](https://devblogs.nvidia.com/deep-learning-self-driving-cars/) module from NVIDIA

The End to End Learning for Self-Driving Cars research paper can be found at (https://arxiv.org/abs/1604.07316)
This repository uses convnets to predict steering angle according to the road. 

1) Autopilot Version 1
2) Autopilot Version 2

### Code Requirements
You can install Conda for python which resolves all the dependencies for machine learning.

##### pip install requirements.txt

### Description
An autonomous car (also known as a driverless car, self-driving car, and robotic car) is a vehicle that is capable of sensing its environment and navigating without human input. Autonomous cars combine a variety of techniques to perceive their surroundings, including radar, laser light, GPS, odometry, and computer vision. Advanced control systems interpret sensory information to identify appropriate navigation paths, as well as obstacles and relevant signage

## Autopilot V1 (Udacity Dataset based on Udacity Simulator)

### Dataset
You can get the dataset at [here](https://d17h27t6h515a5.cloudfront.net/topher/2016/December/584f6edd_data/data.zip)

### Python  Implementation

1) Network Used- Convolutional Network
2) Inspiration - Udacity SDC and End to End Learning for Self-Driving Cars by Nvidia

If you face any problem, kindly raise an issue

### Procedure

1) First, run `LoadData.py` which will get dataset from folder and store it in a pickle file.
2) Now you need to have the data, run `TrainModel.py` which will load data from pickle and augment it. After this, the training process begins.
3) For testing it on the video, run `DriveApp.py`
