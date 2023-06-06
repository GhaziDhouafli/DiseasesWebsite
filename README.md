# Multiple_Disease_Prediction_Website
In this project, I was able to put my skills in both ML and Streamlit to create a website that can tell if the patient has a Parkinson, Diabetes and heart disease.



## **1- Project Organization:**
- Diseases_Prediction_Website
  - README.md                     <- The top-level README for developers using this project.
  - streamlit-code.py             <- Code for the Website.
  - requirements.txt              <- Libraries used in the project.
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
In this part, I employed the SVM (Support Vector Machine) algorithm to make predictions. SVM is a versatile algorithm used for both classification and regression problems. It is capable of solving linear and non-linear problems and has proven effective for various practical applications. The underlying concept of SVM is straightforward: the algorithm constructs a line or hyperplane that separates the data into different classes.

To begin, I divided the data into training and testing sets. I utilized the training data to train the model using the SVM linear algorithm. The training process resulted in an accuracy of 78.33% for the training dataset and 77.27% for the testing dataset. Finally, I saved the trained model using the pickle library for future use.
 
## **3- Heart_Disease_Prediction:**

In this particular section, I utilized Logistic Regression for prediction purposes. Logistic Regression is a type of supervised learning algorithm commonly employed to estimate or predict the probability of a binary event occurring, such as a yes/no outcome.

To begin, I divided the available data into two sets: the training data and the testing data. Subsequently, I employed the training data to train the model using the Logistic Regression algorithm. As a result, I achieved an accuracy of 85.12% for the training dataset and 81.96% for the testing dataset. Finally, I saved the trained model using the pickle library for future reference.
 
 ## **4-Parkinsons_Disease_Prediction:**

In this particular analysis, I employed the Support Vector Machine (SVM) algorithm to make predictions.

To begin, I divided the available data into two sets: the training data and the testing data. Subsequently, I utilized the training data to train the model using the SVM linear algorithm. The training process resulted in an accuracy of 87.17% for the training dataset and 88.2% for the testing dataset.

Finally, to ensure the model's preservation for future use, I saved it using the pickle library.
 
  
 ## **5- Building The Website using Streamlit:**
 Based on the data that we have, i created input texts that covers the whole features that i have. After simply giving all the inputs, you can click on any button and the result will be printed wether this person has a disease or not.
 
 ![Capture](https://user-images.githubusercontent.com/103439643/194719738-5a0e15a1-a3e7-428e-9947-a44cb2006c12.PNG)
 
  ## **6- Usage:**
  The instructions to run the Website on your local system are as follows:
  1. Download or clone this repository into your local system
  2. Run the following command to install necessary libraries for the website to run
      '''pip install -r requirements.txt'''
  4. Run the streamlit app with
      '''streamlit run streamlit-code.py'''
    
  


