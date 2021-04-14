# Thermal_image_recognition
D. S. Breland, S. B. Skriubakken, A. Dayal, A. Jha, P. K. Yalavarthy and L. R. Cenkeramaddi, "Deep Learning-Based Sign Language Digits Recognition From Thermal Images With Edge Computing System," in IEEE Sensors Journal, vol. 21, no. 9, pp. 10445-10453, 1 May1, 2021, doi: 10.1109/JSEN.2021.3061608.

# Introduction
The sign language digits based on hand gestures have been utilized in various applications such as human-computer interaction, robotics, health and medical systems, health assistive technologies, automotive user interfaces, crisis management and disaster relief, entertainment, and contactless communication in smart devices. The color and depth cameras are commonly deployed for hand gesture recognition, but the robust classification of hand gestures under varying illumination is still a challenging task. This work presents the design and deployment of a complete end-to-end edge computing system that can accurately provide the classification of hand gestures captured from thermal images. A thermal dataset of 3200 images was created with each sign language digit having 320 thermal images. In this repository you will find the deep learning model used for claasification of thermal images.The designed model achieves an accuracy of 99.52% on the test data set with an added advantage of accuracy being invariable to background lighting conditions as it is based on thermal imaging.

# Dataset
The dataset consists of 3200 thermal images, 320 images per class. One sample image from each class is shown below. 

| ![](https://github.com/aveen-d/thermal_image_recognition/blob/main/images/dataset/image_0.png) | ![](https://github.com/aveen-d/thermal_image_recognition/blob/main/images/dataset/image_1.png) |
| ![](https://github.com/aveen-d/thermal_image_recognition/blob/main/images/dataset/image_2.png) | ![](https://github.com/aveen-d/thermal_image_recognition/blob/main/images/dataset/image_3.png) |
| ![](https://github.com/aveen-d/thermal_image_recognition/blob/main/images/dataset/image_4.png) | ![](https://github.com/aveen-d/thermal_image_recognition/blob/main/images/dataset/image_5.png) |
| ![](https://github.com/aveen-d/thermal_image_recognition/blob/main/images/dataset/image_6.png) | ![](https://github.com/aveen-d/thermal_image_recognition/blob/main/images/dataset/image_7.png) |
| ![](https://github.com/aveen-d/thermal_image_recognition/blob/main/images/dataset/image_8.png) | ![](https://github.com/aveen-d/thermal_image_recognition/blob/main/images/dataset/image_9.png) |

To get access to the entire dataset please contact the author mentioned below.

# Model Architecture
We develop a CNN model to classify the thermal images. The model architecture is shown below.

| ![alt-text](https://github.com/aveen-d/thermal_image_recognition/blob/main/images/model/model_arch.png) |
# Results
The model was able to achieve an accuracy of 99.52% on test dataset. The accuracy plot of training and validation is shown below.

| ![](https://github.com/aveen-d/thermal_image_recognition/blob/main/images/accuracy/acc_plot.png) |

# How to run
All the code necessary to create and train the model is presented in the main.py file. The trained model can be accesed here https://drive.google.com/file/d/1-0YoSzpZZXgZQhd4F3dwLSlmaQ2ol2_J/view?usp=sharing . 

# Any query, please contact
Aveen Dayal - aveendayal97@gmail.com

