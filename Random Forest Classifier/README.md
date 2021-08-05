## **RANDOM FOREST CLASSIFIER**
<img src='Images/rf9.png'></img>
#### INTRODUCTION
* Random forests or random decision forests are an ensemble learning method for classification, regression and other tasks that 
 operates by constructing a multitude of decision trees at training time. 


#### PURPOSE
* To understand the working of Random Forest Classifier on classification tasks.
* To get equipped with the libraries and practical implementation of the model on various datasets.

#### BREIF EXPLANATION
* Random Forest Classifier is a Supervised Machine Learning Algorithm.
* The forest it builds is an ensemble of Decision Trees usually trained with the bagging method.
* It builds multiple Decision Trees and merges them together to get more accurate and a stable prediction.

#### WORKING CONDITIONS

1. Data Exploration and Analysis.
* Import the libraries and read the data using pandas.

<img src='Images/rf.png'></img>
<img src='Images/rf2.png'></img>
2. Checking For Skewness
* Check for skewness in data. High skewness apparently can hamper model performance.
* Modify the values in skewed features by replacing the values with their square root.

<img src='Images/rf3.png'></img>
3. Splitting the Data into train and test set using sklearns train_test_split.

<img src='Images/rf4.png'></img>
4. Building and Training the model.
* Build the model on default parameters.
* Fit the model and predict on test data set.
* Print classfication report providing information about accuracy,f1-score etc.

<img src='Images/rf5.png'></img>
<img src='Images/rf6.png'></img>
5.Inference and making predictions.
* Plot a confusion matrix to analyze how effectively model makes predictions.
* Confusion matrix provides with true positives,false porsitives, true negatives and false negative values.
* Higher number of True positive and True negative values implies good model performance.

<img src='Images/rf7.png'></img>
<img src='Images/rf8.png'></img>

#### DATASET
Link to the <a href=https://www.kaggle.com/balaka18/email-spam-classification-dataset-csv>Dataset</a>

#### USAGE
* Classification Tasks.
* Feature Selection, Recommendation engines etc.
* Usage in E-Commerce.
* Used in healtcare,banking and stock market.

#### USE CASES
* Tasks where data is non-linear.
* Classification Tasks where we need to predict dicrete values.
* Projects having large amounts of data.

#### LIBRARIES USED
* Pandas
* Numpy
* Matplotlib
* Scikit Learn
* Seaborn

#### ADVANTAGES
* Overfitting probelm is reduced.
* Can automatically handle missing values.
* No feature scaling required.
* Robust to outliers.

#### DISADVANTAGES
* Complexity
* Longer Training Period.

#### APPLICATIONS
* Classification Tasks.
* Business use cases like credit card fraud detection etc.

#### CONCLUSION
* Random Forest Classifier can be used for solving Supervised learning tasks.
* They can be trained on large amount of data and are robust to outliers.
* Labelled Data needs to be provided in order to make predictions.
* Insights can be derived for Business use cases.

#### REFERENCES
* <a href=https://www.kaggle.com/balaka18/email-spam-classification-dataset-csv>Link</a> to the Dataset.
* https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html

### Author


Hey, This is Hrugved Kolhe.

<a href="https://github.com/hrugved06"><img src="https://avatars.githubusercontent.com/u/59966943?s=400&u=445f4a7598547c0ecdeb22a265dd1a3dad9e297d&v=4" width="100px;" alt=""/><br /><sub><b> Hrugved Kolhe</b></sub></a>
</br>

[![GitHub followers](https://img.shields.io/github/followers/hrugved06.svg?label=Follow%20@hrugved06&style=social)](https://github.com/hrugved06)  [![Twitter Follow](https://img.shields.io/twitter/follow/HrugVed_?style=social)](https://twitter.com/HrugVed_)

</br>
<hr style="height:2px;#8080ffborder-width:0;border-radius: 5px;color:gray;background-color:#8080ff">
</br>