## **KNN CLASSIFIER**

**INTRODUCTION**

The k-nearest neighbors (KNN) algorithm is a simple, supervised machine learning algorithm that can be used as for both:
  - classification and 
  - regression problems.

**PURPOSE**

The main prupose is to give a clear understanding on what basically KNN Classifier algorithm is all about, its working, usage, libaries used, advantages, disadvantages etc.


**BRIEF EXPLANATION**
The k-nearest neighbors (KNN) algorithm is a simple, supervised machine learning algorithm that can be used as for both:
  - classification and 
  - regression problems.
   
KNN works by finding the distances between a query and all the examples in the data, selecting the specified number examples (K) closest to the query, then votes for the most frequent label (in the case of classification) or averages the labels (in the case of regression).

**WORKING CONDITIONS**
1.  Data preprocessing and exploration to understand what kind of data will we working on.

- Here we work on preprocessing and exploring the data to understand what kind of data we are working on, it's shape, memory usage, columns, data types etc.
![](https://github.com/ayushi424/DS-ScriptsNook/blob/main/Machine%20Learning/Algorithms/KNN%20Classifier/Images/knn1.jpg)
![](https://github.com/ayushi424/DS-ScriptsNook/blob/main/Machine%20Learning/Algorithms/KNN%20Classifier/Images/knn2.jpg)
2.  Data visualization to draw insights and get better underdstanding on different columns present in the dataset.
![](https://github.com/ayushi424/DS-ScriptsNook/blob/main/Machine%20Learning/Algorithms/KNN%20Classifier/Images/knn3.jpg)
![](https://github.com/ayushi424/DS-ScriptsNook/blob/main/Machine%20Learning/Algorithms/KNN%20Classifier/Images/knn4.jpg)


3. Data training using train-test-split method from sklearn to split the data into training and testing data and then  Model creation using KNN classifier algorithm, where we import the model, then initialize it and fit training data into it and lastly perform predictions on the test data.
![](https://github.com/ayushi424/DS-ScriptsNook/blob/main/Machine%20Learning/Algorithms/KNN%20Classifier/Images/knn5.jpg)

5.  Checking performance by error and accuracy check to find how efficient algorithm performed for this project.

![](https://github.com/ayushi424/DS-ScriptsNook/blob/main/Machine%20Learning/Algorithms/KNN%20Classifier/Images/knn6.jpg)

   - For the dataset being used in this project [click here](https://www.kaggle.com/balakrishcodes/others?select=Movie_classification.csv) 

**USAGE**
- It is basically used for CLASSIFICATION TASKS.
- It is a class capable of performing multi-class classification on a dataset.

**USE CASES**
- Classification tasks.
- Mainly used for complex projects.
- Used in projects where there are more number of features.

**LIBRARIES USED**
- pandas
- matplotlib
- seaborn
- sklearn
- numpy

**ADVANTAGES**

- Easy understand & interpret
- Good for classification tasks


**DISADVANTAGES**

- Can give low accuracy if features are not identified properly.
- Cannot be used for regression projects.

**APPLICATIONS**

- Used in different classification tasks.
- Can help in improving business plan by providing fruitful insights and prediction analysis.

**CONCLUSION**

*  For this project i.e. Movies classification we have used KNN Classification algorithm which is one of the simple and easy classification algorithms.

- The accuracy of KNN model is 60.40%

*  It Can help in improving business plan by providing fruitful insights and prediction analysis.


**REFERENCES**

- For the dataset being used in this project [click here](https://www.kaggle.com/balakrishcodes/others?select=Movie_classification.csv) 
- https://www.javatpoint.com/k-nearest-neighbor-algorithm-for-machine-learning
- https://www.analyticsvidhya.com/blog/2021/04/simple-understanding-and-implementation-of-knn-algorithm/
- https://www.tutorialspoint.com/machine_learning_with_python/machine_learning_with_python_knn_algorithm_finding_nearest_neighbors.htm

**Author**

Hey, This is Hrugved Kolhe.

<a href="https://github.com/hrugved06"><img src="https://avatars.githubusercontent.com/u/59966943?s=400&u=445f4a7598547c0ecdeb22a265dd1a3dad9e297d&v=4" width="100px;" alt=""/><br /><sub><b> Hrugved Kolhe</b></sub></a>
</br>

[![GitHub followers](https://img.shields.io/github/followers/hrugved06.svg?label=Follow%20@hrugved06&style=social)](https://github.com/hrugved06)  [![Twitter Follow](https://img.shields.io/twitter/follow/HrugVed_?style=social)](https://twitter.com/HrugVed_)

</br>
<hr style="height:2px;#8080ffborder-width:0;border-radius: 5px;color:gray;background-color:#8080ff">
</br>