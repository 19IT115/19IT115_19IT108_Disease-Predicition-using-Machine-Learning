# 19IT115-Disease-Predicition-using-Machine-Learning

# Project Overview
In this epidemic time, many individuals avoid to visit hospital. In that case, implementation of such project would be convenient. This project is about ‘Disease Prediction using ML’. Conditions such as Diabetes, Breast Cancer and Covid-19 could be predicted using this project. Importing data or symptoms is the only requirement of the project. This project would lighten the workload even of hospitals.

The ‘Disease Prediction’ project will predict the disease based on information or data provided. It can be derived that the patient has a particular disease or not, on the basis of data provided. This project doesn’t require any knowledge related to medical context.

# Problem and Solution Statement
This project would predict the disease by using patient’s symptoms and general information using dataset. This would provide 80% accurate result by comparing dataset of patient
to previously collected database. Firstly, collected data is prepared into dataset. Then rest of the work could be done by machine learning algorithm such as Decision tree, Random
Forest, etc. User doesn’t need to wait or visit the doctor unlike traditional methods. Even hospitals can use this for fast and almost accurate result.

# Implementation strategy
In Breast cancer prediction first we have to collect the data for machine learning training. then we will select  the features or we also call it as variable selection, it is process of selection of relevent features  for use in model construction. And then we will devide the data into features and target. diagnosis is target and others are features. In "Diagnosis" there is malignant and benign. Here malignant means positive and benign means negative next we will convert M into 1 and B into 0. Now we will devide the data into test and train. we have to devide it randomly because we can not take it in squence. Then we will create blank model of neural network. and then we will train the model. and then we will test it.

In case of diabetes predication procedure is same as breast cancer prediction. but In diabetes prediction we need to do same changes in dataset. And also we have to apply some different activation function.

In Covid-19 prediction we are going to predict it by chest x-ray images. For this we will first prepare a data containing images of chest x-ray. And than we will devide this images into "Two"  parts first on is for training and second one is for validation. In this we will keep 80% of images in training folder. then we will create the Training model and then apply Convolutional neural network. and then Artificial neural network. Then we will Mould the train images. And then we will train the Model. and then for testing it we will add random image of our chest X-ray and then then run it. In our case it is giving us 94% od accuracy.
