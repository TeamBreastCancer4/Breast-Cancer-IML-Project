# Members
1. Zarsha Nazim
2. Abdul Rehman Shehzad
3. Malik Aftab Ali
4. Muhammad Umair Qureshi

# Description
# Different Approaches to predict malignous breast cancers based on Kaggle dataset
This project is started with the goal use machine learning algorithms and learn how to optimize the tuning params and also and hopefully to help some diagnoses.

These are different approaches like:
 + ANN
 + DecisionTree
 + Bayes 
 + KNeighbors
 
Mentioned as the goal of the project is to predict the right way if there are a breast cancer or not.

The whole project is written in Python.
All the parameters of algorithms are tuned at best possible and the Reached accuracy is around ~ 94%.
To be precise the lower Obtained result is around 90% and the best is over 97% with 94% as mean.

This different results are caused by the shuffling of the elements. That is Necessary to make the data more "reals".

Each algorithm work trainset on 70% of initial dataset and it is tested with the 30%.

# Dataset 
the dataset can be found (https://www.kaggle.com/uciml/breast-cancer-wisconsin-data)

# Description about Data

Given data is in excel sheet having integer values as well as floating point values in it. there are total 33 features in given data and 569 rows. 
this dataset contains information about the cells which are taken from mass(fluid) from breast. after injecting out some fluid from breast for observation, this sample is break down using elctronmicroscope and all information regarding those cells have been extracted out which has area, size, perimeter, radius and many such other features about these cells. summarizing, in total 569 samples have been extracted for this deep level observation. 

# How to execute ...
first make sure that code file i.e. imlproject.py and file containing data i.e. data.csv are present in the same file or directory, then set path of anaconda environment to that specific path and then follow the given instruction below: 

To run the scripts you just type in your anaconda environment (prompt):

python imlproject.py

As result of execution the reached accuracy will print

# Execution and Output of Code
while the given code is executed, it sync users with a set of images as well. images which describe the working of code so user can understand easily what is happening. 

(* images are added with names 1.png 2.png 3.png and 4.png) 

the very first image differnetiate between features
second image coorelate features with respect to colouring sceheme, color is given to feature with respect to its distance from another feature.
third image shows accuracy comparison of those classifier which are used in this code (mentioned below)
1. CART classifier 
2. Support Vectore Machine (SVM)
3. Naive Bayes (NB)
4. KNN 
accuracy by each classifier is also shown on console

and then last image again shows comparison of all four classifer, well the accuracy of all the three classifier except SVM are more than 90%, but SVM's fall between 60 ~ 70 % , so data is scaled and then accuracy is calculated again, now this time SVM shows something different to see execute code. ;-)  

SVM is then applied on training dataset and output is in  the form of accuracy which is almost 99% 
