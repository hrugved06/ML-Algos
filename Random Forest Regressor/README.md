## **RANDOM FOREST REGRESSOR**

**INTRODUCTION**

We can use random forest in two types as:

Random Forest Classifier (for classification tasks)

Random Forest Regressor (for regression tasks)


Here we'll implement and understand random forest regressor by using  the labelled data i.e. both input data and output data are provided to the model so that it can learn from the data and then perform accordingly.

**PURPOSE**

The main prupose is to give a clear understanding on what basically random forest regressor algorithm is all about, its working, usage, libaries used, advantages, disadvantages etc.

**BRIEF EXPLANATION**
- We can use random forest in two types as:

    Random Forest Classifier (for classification tasks)

    Random Forest Regressor (for regression tasks)


    Here we'll implement and understand random forest regressor by using  the labelled data i.e. both input data and output data are provided to the model so that it can learn from the data and then perform accordingly.

Let's understand random forest regressor with help of a small project that is prediction of laptop prices.

**WORKING CONDITIONS**
1.  Data preprocessing and exploration to understand what kind of data will we working on.
![](https://github.com/ayushi424/DS-ScriptsNook/blob/main/Machine%20Learning/Algorithms/Random%20Forest%20Regressor/Images/rrr1.jpg)
![](https://github.com/ayushi424/DS-ScriptsNook/blob/main/Machine%20Learning/Algorithms/Random%20Forest%20Regressor/Images/rrr2.jpg)
2.  Data visualization to draw insights and get better underdstanding on different columns present in the dataset.
![](https://github.com/ayushi424/DS-ScriptsNook/blob/main/Machine%20Learning/Algorithms/Random%20Forest%20Regressor/Images/rrr3.jpg)
![](https://github.com/ayushi424/DS-ScriptsNook/blob/main/Machine%20Learning/Algorithms/Random%20Forest%20Regressor/Images/rrr4.jpg)


**Insights drawn:**
*   Most of the laptops are from these three companies- Dell, Lenovo and HP.

*   Maximum Laptops are of 15.6 inches.

*   Resolution of maximum laptops is Full HD 1920x1080.

*   CPU in maximum laptops is Intel core i5.

*   Maximum laptops have RAM of 8 GB.

*   Memory in most of the laptops is 256 GB SSD.


3.  Data Preparation which includes converting categorical columns into numerical, dropping unwanted columns etc.
![](https://github.com/ayushi424/DS-ScriptsNook/blob/main/Machine%20Learning/Algorithms/Random%20Forest%20Regressor/Images/rrr5.jpg)
![](https://github.com/ayushi424/DS-ScriptsNook/blob/main/Machine%20Learning/Algorithms/Random%20Forest%20Regressor/Images/rrr6.jpg)
4.  Data training using train-test-split method from sklearn to split the data into training and testing data & Model creation using linear regression algorithm.
![](https://github.com/ayushi424/DS-ScriptsNook/blob/main/Machine%20Learning/Algorithms/Random%20Forest%20Regressor/Images/rrr7.jpg) 
5.  Checking performance by error and accuracy check to find how efficient algorithm performed for this project.
![](https://github.com/ayushi424/DS-ScriptsNook/blob/main/Machine%20Learning/Algorithms/Random%20Forest%20Regressor/Images/rrr8.jpg)

    For the dataset being used [click here](https://www.kaggle.com/ionaskel/laptop-prices)

**USAGE**
- It is basically used for REGRESSION TASKS

**USE CASES**
- Regression tasks
- Prediction projects.
- Used in projects where there are more number of features.

**LIBRARIES USED**
- pandas
- matplotlib
- seaborn
- sklearn
- numpy

**ADVANTAGES**
- It works well with both categorical and continuous values.
- It automates missing values present in the data.
- Easy understand & interpret
- Good for regression tasks
- Used in prediction projects etc.

**DISADVANTAGES**
- It also requires much time for training as it combines a lot of decision trees to determine the class.
- Relationship between features should be well understood or else it might give low performance efficiency.
- Can give low accuracy if features are not identified properly.
- Cannot be used for classification projects.

**APPLICATIONS**
- Used in Prediction projects such as price prediction, salary predeiction etc.
- Used in different regression tasks.
- Can help in improving business plan by providing fruitful insights and prediction analysis.

**CONCLUSION**
*   Random Forest regressor is one of the efficient models in machine learning.

*   It is useful in regression tasks & various prediction algorithms.

*   It Can help in improving business plan by providing fruitful insights and prediction analysis.


**REFERENCES**

- For the dataset being used [click here](https://www.kaggle.com/ionaskel/laptop-prices)
- https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestRegressor.html
- https://www.mygreatlearning.com/blog/random-forest-algorithm/
- https://www.geeksforgeeks.org/random-forest-regression-in-python/


**Author**


Hey, This is Hrugved Kolhe.

<a href="https://github.com/hrugved06"><img src="https://avatars.githubusercontent.com/u/59966943?s=400&u=445f4a7598547c0ecdeb22a265dd1a3dad9e297d&v=4" width="100px;" alt=""/><br /><sub><b> Hrugved Kolhe</b></sub></a>
</br>

[![GitHub followers](https://img.shields.io/github/followers/hrugved06.svg?label=Follow%20@hrugved06&style=social)](https://github.com/hrugved06)  [![Twitter Follow](https://img.shields.io/twitter/follow/HrugVed_?style=social)](https://twitter.com/HrugVed_)

</br>
<hr style="height:2px;#8080ffborder-width:0;border-radius: 5px;color:gray;background-color:#8080ff">
</br>