# 👀 Object Detection by Using YOLOv5

## 🗣 Project Overview
1. Conduct an entire object detection since the start such as generating a data from scratch, labeling the data
manually and augmentation by using website called Roboflow.
2. Using Google Colab environment and import data from Roboflow by using API.
3. Training the data by using 2 seperate models and visualizing which is
    -  Training from scratch
    - Using Transfer Learning
4. Predict test dataset and save the model for further use.

Most of the project have been developed on Google Colab and Roboflow platform so you could check on the Google Colab link that
appears on the badge above. My colab would be describe in very detailed.

![result_0](https://github.com/northpr/object_detection_yolov5/blob/main/model/data/markdown_image/germany_map.png)

**I would highly recommend to check the colab for in high-level**

## What we expected for this repo.
- What is YOLOv5 and understanding the process of how doing object detection since the start.
- Create a different model and making comparison between it.
- Feature Engineering from original image data by using data augmentation technique.
- Save the model that we've been trained for further used

## 👨‍💻 Code,Tools and Resource
Python, YOLOv5 (Object Detection Libraries), Roboflow (Data Preparation) and Google Colab.

## 📕 Contents
You could check all of the work in this Colab link

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1lIyiZXBO2Rm22A_skLWvlL_sVQWR1YBC?usp=sharing)

# 🏋️‍♂️ Small brief of the work
## 📸 Data Collection
Hundred of photos have taking that don’t contain any specific condition, only with white background of products to train and test. 
![data_collection_roboflow](https://github.com/northpr/object_detection_yolov5/blob/main/model/data/markdown_image/germany_map.png)

## 🧮 Result
Here's some results from the work. I’m trying to improve the quality of the detections by increasing the number of photos from different angles and positions. The accuracy could be improved by increasing the number of images to meet the recommendation of the libraries (YOLOv5).

Confusion Matrix
![confusion_matrix](https://github.com/northpr/object_detection_yolov5/blob/main/model/data/markdown_image/germany_map.png)

F1-Score
![model1_f1](https://github.com/northpr/object_detection_yolov5/blob/main/model/data/markdown_image/germany_map.png)

Detection on testing photo and result

![result_1](https://github.com/northpr/object_detection_yolov5/blob/main/model/data/markdown_image/germany_map.png)
![result_2](https://github.com/northpr/object_detection_yolov5/blob/main/model/data/markdown_image/germany_map.png)
