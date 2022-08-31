# 👀 Object Detection by Using YOLOv5

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1lIyiZXBO2Rm22A_skLWvlL_sVQWR1YBC?usp=sharing)

## 🗣 Project Overview
1. Conduct an entire object detection from the start, such as generating data from scratch, labeling the data
manually and augmentation by using a website called Roboflow.
2. Using Google Colab environment and importing data from Roboflow using API.
3. Training the data by using two seperate models and visualizing which is
    -  Training from scratch
    - Using Transfer Learning
4. Predict the test dataset and save the model for further use.

Most of the projects have been developed on Google Colab and Roboflow platform so that you can check the Google Colab link on the badge above. My Colab will be described in very detail.

![result_0](https://github.com/northpr/object_detection_yolov5/blob/master/image/result_0.jpeg?raw=true)

**I would highly recommend to check the Colab for in high-level**

## What we expected for this repo.
- What is YOLOv5, and understanding the object detection process from the start?
- Create a different model and make a comparison between it.
- Feature Engineering from original image data by using the data augmentation technique.
- Save the model that we've been trained for further use.

## 👨‍💻 Code,Tools and Resource
Python, YOLOv5 (Object Detection Libraries), Roboflow (Data Preparation) and Google Colab.

## 📕 Contents
You could check all of the work in this Colab link

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1lIyiZXBO2Rm22A_skLWvlL_sVQWR1YBC?usp=sharing)

# 🏋️‍♂️ Small brief of the work
## 📸 Data Collection
Hundred of photos have taken that don’t contain any specific condition, only with white background of products to train and test. 
![data_collection_roboflow](https://github.com/northpr/object_detection_yolov5/blob/master/image/data_collection_roboflow.png?raw=true)

## 🧮 Result
Here are some results from work. I’m trying to improve the quality of the detections by increasing the number of photos from different angles and positions. The accuracy could be improved by increasing the number of images to meet the recommendation of the libraries (YOLOv5).

### 👍 Some result from the test dataset.
Confusion Matrix
![confusion_matrix](https://github.com/northpr/object_detection_yolov5/blob/master/image/confusion_matrix.png?raw=true)

F1-Score
![model1_f1](https://github.com/northpr/object_detection_yolov5/blob/master/image/model1_f1.png?raw=true)

Detection on testing photo and result

![result_1](https://github.com/northpr/object_detection_yolov5/blob/master/image/result_1.jpeg?raw=true)
![result_2](https://github.com/northpr/object_detection_yolov5/blob/master/image/result_2.jpeg?raw=true)
