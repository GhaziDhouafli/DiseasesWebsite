# Multiple_Disease_Prediction_Website
In this project, I was able to put my skills in both ML and Streamlit to create a website that can tell if the patient has a Parkinson, Diabetes and heart disease .First of all i begin by getting the data from kaggle (It's uploaded in the repository) and trying to make models to make the predictions.

## **1- Diabetes_Disease_Prediction:**
For this part, I used SVM or Support Vector Machine algorithm to make predictions. SVM is a linear model for classification and regression problems. It can solve linear and non-linear problems and work well for many practical problems. The idea of SVM is simple: The algorithm creates a line or a hyperplane which separates the data into classes.


![support-vector-machine-algorithm](https://user-images.githubusercontent.com/103439643/190227796-25e76039-1180-4847-9cb9-8b139f9688cd.png)

 I started by spliting the data into train and test data. I used the train data to train the model based on the SVM linear algorithm and i ended up with a 78,33% accuracy for the training data-set and 77.27% for the testing data-set. At the end, i saved the model using the pickle library.
 
## **2- Heart_Disease_Prediction:**
For this part, I used the  Logistic Regression to make predictions. Logistic Regression is an example of supervised learning. It is used to calculate or predict the probability of a binary(yes/no) event occurring.

![1_3FgpptTWzpd2RLgKbV-HvA](https://user-images.githubusercontent.com/103439643/194719077-60cec236-b7c5-45d4-a4ba-7fb52d70c4ad.jpg)

 I started by spliting the data into train and test data. I used the train data to train the model based on the Logistic Regnression algorithm and i ended up with a 85.12% accuracy for the training data-set and 81.96% for the testing data-set. At the end, i saved the model using the pickle library.
 
 ## **3-Parkinsons_Disease_Prediction:**
 For this part, I used SVM or Support Vector Machine algorithm to make predictions.
 I started by spliting the data into train and test data. I used the train data to train the model based on the SVM linear algorithm and i ended up with a 87.17% accuracy for the training data-set and 88.2% for the testing data-set. At the end, i saved the model using the pickle library.
 
  
 ## **4- Building The Website using Streamlit:**
 Based on the data that we have, i created input texts that covers the whole features that i have. After simply giving all the inputs, you can click on any button and the result will be printed wether this person has a disease or not.
 
 ![Capture](https://user-images.githubusercontent.com/103439643/194719738-5a0e15a1-a3e7-428e-9947-a44cb2006c12.PNG)


