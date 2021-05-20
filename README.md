# Face-Recognition

Face recognition is a computer vision that helps to locate/visualize human face. Face recognition is a method of identifying or verifying the identity of an individual using their face. Face recognition systems can be used to identify people in photos, video, or in real-time.There are various algorithms that can do face recognition but their accuracy might vary. We use face embedding in which each face is converted into a vector and this technique is called deep metric learning.
OpenCV is a Library which is used to carry out image processing using programming languages like python. This project utilizes OpenCV Library to make a Real-Time Face Detection using your webcam as a primary camera.

## Steps involved in this project:
In this project the task is to detect student face and to note down that student roll number in excel file. I have created dataset of 10 student images and then performed following steps:   
1. Face detection: The very first task we perform is detecting faces in the image or video stream.
2. Feature Extraction: Now that we have cropped the face out of the image, we extract features from it. We are using face embeddings to extract the features out of the face. A neural network takes an image of the person’s face as input and outputs a vector which represents the most important features of a face. In machine learning, this vector is called embedding and thus we call this vector as face embedding. 
3. Comparing faces: Now that we have face embeddings for every face in our data saved in a file, the next step is to recognise a new  image. So the first step is to compute the face embedding for the image using the same network we used above and then compare this embedding with the rest of the embeddings we have. 
4. Creating excel file : Once we recognise the image now we have to note down that particular roll number in excel sheet. 

### Python libraries used are : OpenCV,facerecognition,dlib,Numpy
