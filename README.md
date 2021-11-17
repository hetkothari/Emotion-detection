# Face-Emotion-Detection

# Introduction
Emotion recognition is the process of identifying human emotion. People vary widely in their accuracy at recognizing the emotions of others. Use of technology to help people with emotion recognition is a relatively nascent research area. Generally, the technology works best if it uses multiple modalities in context. To date, the most work has been conducted on automating the recognition of facial expressions from video, spoken expressions from audio, written expressions from text, and physiology as measured by wearables.

Facial expressions are a form of nonverbal communication. Various studies have been done for the classification of these facial expressions. There is strong evidence for the universal facial expressions of seven emotions which include: neutral happy, sadness, anger, disgust, fear, and surprise. So it is very important to detect these emotions on the face as it has wide applications in the field of Computer Vision and Artificial Intelligence. These fields are researching on the facial emotions to get the sentiments of the humans automatically.

# Dataset Information
The data comes from the past Kaggle competition “Challenges in Representation Learning: Facial Expression Recognition Challenge”: we have defined the image size to 48 so each image will be reduced to a size of 48x48.The faces have been automatically registered so that the face is more or less centered and occupies about the same amount of space in each image. Each image corresponds to a facial expression in one of seven categories (0=Angry, 1=Disgust, 2=Fear, 3=Happy, 4=Sad, 5=Surprise, 6=Neutral). The dataset contains approximately 36K images. Dataset link - https://www.kaggle.com/msambare/fer2013

# Dependencies
Python 3
Tensorflow 2.0
Streamlit
Streamlit-Webrtc
OpenCV

# Building Deep Learning Model Using CNN
In deep learning, a convolutional neural network (CNN, or ConvNet) is a class of deep neural network, most commonly applied to analyze visual imagery. They have applications in image and video recognition, recommender systems, image classification, image segmentation, medical image analysis, natural language processing, brain-computer interfaces, and financial time series.
Classic NNs are usually composed of several fully connected layers. This means that every node of one layer is connected to all the nodes of the next layer. Convolutional Neural Networks also have Convolutional layers that apply sliding functions to groups of pixels that are next to each other.

![image](https://user-images.githubusercontent.com/64547004/142170180-ef831f75-412a-45a6-b425-15f7cf0e7dc5.png)

# CNN Architecture
![image](https://user-images.githubusercontent.com/64547004/142170339-df181400-fbf4-4e0a-9a47-6e5478521a49.png)

# Deployment
I've deployed the model over Heroku and also streamlit platform with the help of buildpack-apt which is necessary to deploy opencv model on heroku and streamlit.

Deployment Link for Heroku - https://face-emotion1.herokuapp.com

Deploymenet link for streamlit - https://share.streamlit.io/sumayabai/face-emotion-detection/main/app.py

# Output
![streamlit-snapshot](https://user-images.githubusercontent.com/64547004/142171177-25ea6aa8-5121-4c57-a8c9-225dcdc6fec5.png)
