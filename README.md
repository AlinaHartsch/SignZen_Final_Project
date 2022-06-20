# SignZen
Final Project Ironhack Data Analytics Bootcamp


## Project Overview
SignZen is a real-time online sign language translator that detects sign language (ASL) via camera and translates it into English. It also provides text-to-sign translation by letting the user enter an English word and returning an image of the corresponding sign.

The vision behind this project is to use Machine Learning to work towards are more inclusive society. With over 70 million deaf people around the globe, most language technology and online translators do not cater to deaf people’s needs. This project wants to take the first step in tackling this problem and provide a communication tool that fosters easier communication and interaction between deaf and hearing people.

The result is a first MVP and the translation scope, for now, includes the following words/sentences:
• Hello
• Yes
• No
• I love you
• Thank you
• My name is

## Image dataset & labeling
1250 pictures were manually taken with Python & OpenCV. 
For annotation, augmentation, splitting into test - validation - training sets and feeding the data into the model, the computer vision developer framework Roboflow was used. 

## Training 
This machine learning project was created using Python and a pre-trained model from YOLOv5 in PyTorch, that was custom trained with the dataset prepared in Roboflow.(https://colab.research.google.com/github/roboflow-ai/yolov5-custom-training-tutorial/blob/main/yolov5-custom-training.ipynb)
See the YOLOv5 Docs for full documentation on training, testing, and deployment: https://docs.ultralytics.com/

## Web Application 
The web application was created using Python, Flask and HTML. For the styling CSS and Boostrap (including this template: https://codepen.io/cms287/pen/OZOeLz) were used.

