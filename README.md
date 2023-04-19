# SVM_Parameter_Optimisation
Assignment for UCS654

## About SVM and Parameter Optimization

Support Vector Machine or SVM is one of the most popular Supervised Learning algorithms, which is used for Classification as well as Regression problems. However, primarily, it is used for Classification problems in Machine Learning.

Some of the most important parameters of SVM such as kernel, C, and gamma can be changed in order to achieve a higher accuracy. This is called as Hyperparameter Tuning. 

We can perform this task using GridSearchCV for optimizing these parameters.

In this python file, I've used a Fitness Function to optimize the parameters.

## Dataset

The dataset for the project has been downloaded from the UCI Machine Learning Repository.
https://archive.ics.uci.edu/ml/machine-learning-databases/00602/

Images of 13,611 grains of 7 different registered dry beans were taken with a high-resolution camera.Seven different types of dry beans were used in this research, taking into account the features such as form, shape, type, and structure by the market situation.

## Final Result Table

| Sample  | Best Accuracy | Best Kernel | Best Nu | Best Epsilon |
| -----   | ------------- | ----------- | ------- | ------------ |
| 1 | 0.60 | Linear | 6.85 | 4.32 |
| 2 | 0.62 | Linear | 8.73 | 4.24 |
| 3 | 0.51 | Linear | 0.64 | 7.69 |
| 4 | 0.38 | Poly   | 3.46 | 1.97 |
| 5 | 0.53 | Linear | 5.24 | 8.22 |
| 6 | 0.39 | Linear | 7.01 | 0.17 |
| 7 | 0.48 | Linear | 7.59 | 9.86 |
| 8 | 0.24 | Linear | 5.96 | 4.99 |
| 9 | 0.24 | Linear | 3.62 | 2.31 |
| 10| 0.21 | rbf    | 6.48 | 8.05 |

The graph is made for the sample which has best accuracy. Sample 2 has the best accuracy of 0.62 having kernel = Linear, Nu = 8.73 and Epsilon = 4.24.

## Convergence Graph
<img src="https://user-images.githubusercontent.com/88177851/233162659-242575fe-2e23-4e4f-9c54-eceec9cba39c.png" width="500">


## Datatypes of every column of the dataset:
he datatypes of attributes is examined and is plotted to depict the variations among columns based on datatypes.
Here 0.5 means that data is numerical and 0 means it is categorical data.
<img src="https://user-images.githubusercontent.com/88177851/233163254-6baa6379-9c14-44a7-abf3-8bd293d7a1d9.png">

## Percentage of every class present in dataset:
The distribution of seven classes present in the dataset can be analysed by viewing their percentage in the data.
<img src="https://user-images.githubusercontent.com/88177851/233163568-4ca51911-95a5-47f4-b6ba-6180d3e2cd7b.png">



## Correlation between attributes of the data:
Analysing correlations and then removing the columns which are highly correlated with another.
<img src="https://user-images.githubusercontent.com/88177851/233164079-3037d5c7-9245-4d5e-9d22-3c5dd82be1b6.png">


## Written By
Name : Nandini Goel
  
Roll No. : 102017101

Sub-Group: 3CS5
