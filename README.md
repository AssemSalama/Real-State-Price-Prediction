## 1️⃣ Project Motive:
- Creating a Machine Learning model to predict the home prices in Bangalore, India. We are going to use the dataset from Kaggle.com. We are also going to create a single page website which will provide the front end to access our model for predictions.

## 2️⃣ Project Structure : 
1. Data loading and cleaning
2. Outlier detection and removal
3. Feature engineering
4. Dimensionality reduction
5. Gridsearchcv for hyperparameter tunning
6. K fold cross validation

## 3️⃣ Project Steps:
'''
Step1: Import the required libraries
Step2: Load the data
Step3: - Understand the data
       - drop unnecessary columns
Step4: - Data Cleaning
        - Check for na values
        - Verify unique values of each column
        - Make sure values are correct (eg. 23 BHK home with 2000 Sqrft size is worng)
        - Feature Engineering
        - Dimesionality Reduction
        - Outlier removal using domain knowledge (2bhk price < 3bhk price, size per bhk >= 300 sqft)
        - Outlier removal using standard eviation and mean
        - One Hot encoding
Step5: Build Machine Learning Model
Step6: Testing The model
Step7: Export the model
'''
