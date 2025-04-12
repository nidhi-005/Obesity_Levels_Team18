# Team 18: Obesity Level Classification and Clustering Analysis

![c7891bdff7df7ad332c0fb71177adbf2](https://github.com/user-attachments/assets/315853ed-2f4a-49b0-96e9-d2c5d89ffbcc)

# Problem Statement
Obesity Level Estimation dataset contains health-related information from individuals with ages ranging from 14 to 61 years. 

The goal is to predict obesity levels and segment individuals based on their health characteristics.

In this project we present our analysis of the data. We have employed some of the most widely used classification algorithms for this project namely;
* Logistic Regression
* SVM
* Descison tree
* KNN
* Naive Bayes
* Random Forest

# EDA
In EDA we divided analysis into several part to get better idea about data like we checked distribution of numerical and categorical data checked relationship between independent and dependent variable. We used box plots to visualize how each feature was distributed over each of the two target classes. This gave us a clear idea as to which variable was contributing more. We also used bar plot to check the distribution of category of the independent variable into dataset and also checked their relationship with dependent variable to understand what factors are contributing for different cause.

# Feature Engineering
After that we perform feature engineering, in feature engineering we created some new feature from available features with the goal of simplifying and speeding up data transformation while also improving model performance. Then we used oversampling technique to handle class imbalance to make classes even for training model. As our data was highly Imbalance, We used Random Over Sampler Technique to balance our training set before training model.

After feature engineering we selected feature to use to train our model and encoded categorical variables as ML model works with numerical data to do computation. We used label encoding and one hot encoding.

# Model Training and Testing
Finally we started the machine learning part on the choosen feature subsets, did cross validation for each of the models' hyperparameters and recorded the performance in each case into a compact dataframe. The evaluation metrics we chose for our project include precision, recall, f1-score Benchmarked Random Forest Classifier algorithm .

**Random Forest is an ensemble learning method used for classification and regression tasks. It operates by building multiple decision trees during training and combining their outputs to improve accuracy and prevent overfitting. This algorithm is robust to noise, handles missing data well, and excels in scenarios with large datasets and high-dimensional features. It is widely valued for its ability to provide feature importance scores, aiding in interpretability**
