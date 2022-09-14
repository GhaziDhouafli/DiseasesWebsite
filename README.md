# Parkinsons_Disease_Prediction_Website
In this project, I was able to put my skills in both ML and Streamlit to create a website that can tell you wether or not the person has the parkinsons disease.First of all i begin by getting the data from kaggle (It's uploaded in the repository) and trying to make a model based on it that can predict the disease.

## **1- Support Vector Machine (SVM):**
SVM or Support Vector Machine is a linear model for classification and regression problems. It can solve linear and non-linear problems and work well for many practical problems. The idea of SVM is simple: The algorithm creates a line or a hyperplane which separates the data into classes.

![support-vector-machine-algorithm](https://user-images.githubusercontent.com/103439643/190227796-25e76039-1180-4847-9cb9-8b139f9688cd.png)

## **2- Building The Model:**
 I started by spliting the data into train and test data. I used the train data to train the model based on the SVM linear algorithm and i ended up with an 87% accuracy
 which is pretty good result. At the end, i saved the model using the pickle library.
 
 ## **3- Building The Website using Streamlit:**
 Based on the data that we have, i created input texts that covers the whole features that i have. After simply giving all the inputs, you can click on the "Parkinson's Test Result" button and the result will be printed wether this person has the Parkinsons disease or not.
 
 
