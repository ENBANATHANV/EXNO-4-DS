# EXNO:4-DS
# AIM:
To read the given data and perform Feature Scaling and Feature Selection process and save the
data to a file.

# ALGORITHM:
STEP 1:Read the given Data.
STEP 2:Clean the Data Set using Data Cleaning Process.
STEP 3:Apply Feature Scaling for the feature in the data set.
STEP 4:Apply Feature Selection for the feature in the data set.
STEP 5:Save the data to the file.

# FEATURE SCALING:
1. Standard Scaler: It is also called Z-score normalization. It calculates the z-score of each value and replaces the value with the calculated Z-score. The features are then rescaled with x̄ =0 and σ=1
2. MinMaxScaler: It is also referred to as Normalization. The features are scaled between 0 and 1. Here, the mean value remains same as in Standardization, that is,0.
3. Maximum absolute scaling: Maximum absolute scaling scales the data to its maximum value; that is,it divides every observation by the maximum value of the variable.The result of the preceding transformation is a distribution in which the values vary approximately within the range of -1 to 1.
4. RobustScaler: RobustScaler transforms the feature vector by subtracting the median and then dividing by the interquartile range (75% value — 25% value).

# FEATURE SELECTION:
Feature selection is to find the best set of features that allows one to build useful models. Selecting the best features helps the model to perform well.
The feature selection techniques used are:
1.Filter Method
2.Wrapper Method
3.Embedded Method

# CODING AND OUTPUT:
![Screenshot 2025-04-18 105101](https://github.com/user-attachments/assets/64771e63-d60a-44e8-a6d7-9a1426aec243)
![Screenshot 2025-04-18 105114](https://github.com/user-attachments/assets/f016e88c-8417-42d2-bbfc-d600b42f5a7b)
![Screenshot 2025-04-18 105131](https://github.com/user-attachments/assets/fb28a18b-936d-4204-a8be-98446aadaace)
![Screenshot 2025-04-18 105145](https://github.com/user-attachments/assets/9bf3c2c8-7675-487e-9a9b-78e1c67691e0)
![Screenshot 2025-04-18 105159](https://github.com/user-attachments/assets/1c643d06-8e5d-4dc9-a924-833ba746e7c7)
![Screenshot 2025-04-18 105208](https://github.com/user-attachments/assets/ada7c8cf-5c17-45a9-a2d2-f90f288da681)
    
# RESULT:
       Feature scaling and Feature selection process sucessfully completed.
