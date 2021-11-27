# Diabetes-disease-detection

The data source is from kaggle and the csv file of diabetes data is found in this repository. The code snippet of the following  project is found also on this repository as " Untitled.iypnb".

# Goal

Our objective is to detect diabetes with precision and accuracy.
Therefore, we are going to build machine learning algorithims to predict the disease.

Three machine models:

a) Logistcs regression

b) K-nearest neghbor

c) Support vector machines: linear and RBF kernel

# Find the best correlated factors for diabetes 

To find the correlated factors, we can use corr() and build he correlation matrix.

The 3 top correlated facors the most influential on diabetes are: glucosee, age and BMI. Therefore we will include only these factors in our model.
![image](https://user-images.githubusercontent.com/53411455/143719668-48d1f0f7-81be-4d59-95f4-fc14cf4f5c7f.png)

# Logistc regression

The result of training the model should use an average of 0.7617737525632263.


# K-nearest neighbor

The optimal number of neighbors is 19
0.7721462747778537


# Suppor vector machine 

## linear kernel 
The  accuracy of:
0.7656527682843473

## RBF kernel:

The accuracy of:
0.6353725222146275

![image](https://user-images.githubusercontent.com/53411455/143719674-6bdfd3e4-6671-46c3-8b41-b1b18625d1c7.png)


Therefore, the best perfoming model  is K-nearest neighbor


# Conclusion

The best performing machine learning model allowed us to predict diabetes dssease according to three most influential factors :glucose level in the blood, age of the person and BMI (weight of the person).






