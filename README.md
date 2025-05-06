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
       ![Screenshot 2025-05-06 205600](https://github.com/user-attachments/assets/edf5e57e-4b27-41c2-b4d1-eb15dbe6782e)
       ![Screenshot 2025-05-06 205612](https://github.com/user-attachments/assets/c9da9ca3-f432-469a-b78f-f6bec7484fca)
       ![Screenshot 2025-05-06 205643](https://github.com/user-attachments/assets/5a26a039-c886-48d4-ba91-79a8389ebd24)
       ![Screenshot 2025-05-06 205649](https://github.com/user-attachments/assets/af426f9d-16de-4bf9-85a6-b16d2009c7c3)
       ![Screenshot 2025-05-06 205700](https://github.com/user-attachments/assets/a9284a16-5de9-427f-91a1-3eb7a429da6b)
       ![Screenshot 2025-05-06 205707](https://github.com/user-attachments/assets/b18beaa8-37eb-4224-925f-ea40bed31b38)
       ![Screenshot 2025-05-06 205728](https://github.com/user-attachments/assets/38f18013-b945-4401-a6dd-828a3c1055e9)







# RESULT:
      Thus, Feature Scaling and Feature Selection has been used on the given data set.
