# Multiple_Disease_Prediction_Website
In this project, I was able to put my skills in both ML and Streamlit to create a website that can tell if the patient has a Parkinson, Diabetes and heart disease.



## **1- Project Organization:**
- Diseases_Prediction_Website
  - README.md                     <- The top-level README for developers using this project.
  - streamlit-code.py             <- Code for the Website.
  - datasets                      <- Datasets folder.
    - diabetes.csv              <- Dataset for diabetes disease.
    - heart.csv                 <- Dataset for heart disease.
    - parkinsons.csv            <- Dataset for parkinsons disease.
  - disease prediction code       <- Folder for the Jupyter Notebooks.
    - Parkinsons.ipynb          <- Parkinsons prediction notebook.
    - diabetes.ipynb            <- diabetes prediction notebook.
    - heart.ipynb               <- heart disease prediction notebook.
  - saved models                  <- Folder for the saved models.
    - diabetes_model.sav        <- Model for diabetes prediction.
    - heart_disease_model.sav   <- Model for heart disease prediction.
    - parkinsons_model.sav      <- Model for parkinsons prediction.
       
## **2- Diabetes_Disease_Prediction:**
For this part, I used SVM or Support Vector Machine algorithm to make predictions. SVM is a linear model for classification and regression problems. It can solve linear and non-linear problems and work well for many practical problems. The idea of SVM is simple: The algorithm creates a line or a hyperplane which separates the data into classes.

 I started by spliting the data into train and test data. I used the train data to train the model based on the SVM linear algorithm and i ended up with a 78,33% accuracy for the training data-set and 77.27% for the testing data-set. At the end, i saved the model using the pickle library.
 
## **3- Heart_Disease_Prediction:**
For this part, I used the  Logistic Regression to make predictions. Logistic Regression is an example of supervised learning. It is used to calculate or predict the probability of a binary(yes/no) event occurring.

 I started by spliting the data into train and test data. I used the train data to train the model based on the Logistic Regnression algorithm and i ended up with a 85.12% accuracy for the training data-set and 81.96% for the testing data-set. At the end, i saved the model using the pickle library.
 
 ## **4-Parkinsons_Disease_Prediction:**
 For this part, I used SVM or Support Vector Machine algorithm to make predictions.
 I started by spliting the data into train and test data. I used the train data to train the model based on the SVM linear algorithm and i ended up with a 87.17% accuracy for the training data-set and 88.2% for the testing data-set. At the end, i saved the model using the pickle library.
 
  
 ## **5- Building The Website using Streamlit:**
 Based on the data that we have, i created input texts that covers the whole features that i have. After simply giving all the inputs, you can click on any button and the result will be printed wether this person has a disease or not.
 
 ![Capture](https://user-images.githubusercontent.com/103439643/194719738-5a0e15a1-a3e7-428e-9947-a44cb2006c12.PNG)


