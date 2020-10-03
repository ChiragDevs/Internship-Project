# Internship-Project
Internship Project on Breast Cancer Classification using Deep Learning
The project classifies the given set of data in the form of imgages organised based on the patients trials.
The breast cancer is mostly caused by IDC which is found in the milk stream.
The cancer is determined from the images based on the depth and variation in color.
The collected images are organised into 0 and 1 folders based on positivity towards breast cancer by 1 and negativity by 0.

Initially create the folder dataset and unzip the datatset to the folder
Import the required  libraries initially

The project begins by creating validation, training and the testing dataset.The separating is done by configuration code
The training dataset is used to train about how positive cancer looks like and how negative trials appear.
The validation dataset is used to validation is used to validate the trained machine.
The testing dataset is used to test the working and get the accuracy of the classification.
The configuration code takes the dataset folder path as input and creates a folder idc in the same directory which contains the 3 required folders.

The build dataset uses the configuration code and places respective image files in their respecctive folder directories

Nexxt a Covolution Neural Network call CancerNet is built.The neural network is able to differentiate each image from other based defined properties.
This helps in the process of teaining, validating and testing.This neural network uses the keras library to process images.

Finally the training is done and the confusion matrix in recieved.
