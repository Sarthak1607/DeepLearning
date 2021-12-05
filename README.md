## DeepLearning


## FACE MASK DETECTION
## Content
  * [Abstract](#Abstract)
  * [Project_Overview](#Project_Overview)
  * [Dataset](#Dataset)
  * [Data_Pre-processing](#Data_Pre-processing)
  * [CNN Architecture](#CNN_Architecture)
  * [Loss_and_Accuracy_Plot](#Loss_and_Accuracy_Plot)
  * [Applications](#Applications)
## Abstract

Post covid, many establishments are finding it hard to detect protocol violations, as the time and labour spent for the same incurrs high cost and is highly inefficient. The main aim of this project is to detect violations, like not wearing a mask in a workplace, and notify the officials. The projected is implemented in Python using Keras, Tensorflow and OpenCV. 

## Project Overview

An image with a face is fed to a cascade classifier which identifies the Region of Interest (ROI) and give the coordinates of the detected face along with the height and width parameters. This is further resized to a 100x100 image and fed to the pre-trained CNN model, which will provide an output as 'With mask' or 'Without mask'.

## Dataset

The dataset consisted of 1376 images, 690 face images with masks and 686 without masks. 
The original dataset is prepared by Prajna Bhandary and available at Github.

## Data Preprocessing

The ROI image is converted to grayscale and then resized to 100x100. This is then reshaped to a 4D array input to be fed to the CNN model. 
2 categories are created as 'with mask' and 'without mask'.
## CNN Architecture

 ![image](https://user-images.githubusercontent.com/62449953/144737157-42a3feea-ea5c-490a-ba3d-de034e1e4e71.png)

## Loss & Accuracy Plot

![image](https://user-images.githubusercontent.com/62449953/144737120-115917e1-a4e8-4779-9402-5a9e1830b9fe.png)
![image](https://user-images.githubusercontent.com/62449953/144737130-7eda9fd7-ec17-4e8f-a85c-3bb2511cab49.png)

   
## Project Demo Video Link
![image](https://user-images.githubusercontent.com/62449953/144737162-0ccca945-b26b-4936-ad0b-04d90379cb93.png)


**## Application**

Airports
The Face Mask Detection System can be used at airports to detect travelers without masks. If a traveler is found to be without a face mask, their picture is sent to the airport authorities so that they could take quick action. 
Hospitals
Using Face Mask Detection System, Hospitals can monitor if their staff is wearing masks during their shift or not. Can be used to monitor quarantine people as well
Offices
The Face Mask Detection System can be used at office premises to detect if employees are maintaining safety standards at work. 
It monitors employees without masks and sends them a reminder to wear a mask. The reports can be downloaded or sent an email at the end of the day to capture people who are not complying with the regulations or the requirements. 




