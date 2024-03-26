# Day Dusk Night Classification
Author: [Ng Zheng Jue](https://github.com/xinjue37), [Ong Ming Jie](https://github.com/ethanong98), [Ng Rui Qi](https://github.com/Ruiqi2002), [Tan Hong Guan](https://github.com/tanhg1116)

* This is a project developed in undergraduate Year 2 - Semester 2
* This is a Day Dusk Night Classifier implemented using CNN (Pytorch) with autoencoder & ensemble learning.
* This repository consists of
  - Database which consists the image of Day, Dusk, Night captured by ourself
  - Difference jupyter notebook file with difference settings in preprocessing the image

# Motivation of building this classifier
In recent years, researchers have found a surge of interest in day/night monitoring systems. One of the reasons is that it can help in computer-vision-based traffic monitoring systems. Recently, the accuracy of computer-vision-based traffic monitoring systems in segmenting the vehicles has been extremely low. This is due to the lighting conditions, which have an impact on the model's performance. One of the practical solutions is to switch the algorithms for daytime when the illumination is high and for night-time when the illumination is low. Therefore, by implementing a day/night monitoring system, the government can apply different algorithms for different illumination conditions for the traffic system to improve traffic flow.

However, the day/night detector currently has several flaws, namely that models do not consider the presence of dusk. By including dusk as one of the classes, we can differentiate between the two examples above and produce a more efficient and time-saving system. Take the implementation of traffic flow as an example. If the system can identify that it is dusk, it can switch to an algorithm that can decrease the congestion level during rush hour. Thus, we has initialised this project to construct a model for this day/night detector, which also includes the class "dusk."
