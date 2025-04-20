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
![Ds exp 4 ipynb - Colab_page-0001](https://github.com/user-attachments/assets/95c36626-ef07-4d1a-bba2-d6ed4b1b25de)
![Ds exp 4 ipynb - Colab_page-0002](https://github.com/user-attachments/assets/ff575441-5293-4532-99bf-224c5c0aad92)
![Ds exp 4 ipynb - Colab_page-0003](https://github.com/user-attachments/assets/baa9daa7-d7b6-40d3-a604-6071a4f6227e)
![Ds exp 4 ipynb - Colab_page-0004](https://github.com/user-attachments/assets/69a1fb2b-61c3-4fe6-bb42-ae6548c973bd)
![Ds exp 4 ipynb - Colab_page-0005](https://github.com/user-attachments/assets/d8ea2ddb-9e38-441f-a96a-6b98863e6f9d)
![Ds exp 4 ipynb - Colab_page-0006](https://github.com/user-attachments/assets/aa986ac6-2f59-4ae9-b626-e2b6776fa924)

# RESULT:
Thus we have read and performed  Feature Scaling and Feature Selection process.
