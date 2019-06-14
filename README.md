# CS273P UCI Machine Learning Project, Spring 2019

Dataset:[I'm an inline-style link](https://archive.ics.uci.edu/ml/datasets/diabetes+130-us+hospitals+for+years+1999-2008)

Files:
1. preprocess.ipynb - Data Preprocessing
2. decisionTree.ipynb - Decision Tree Classifier 
3. decisionTree_PCA.ipynb - Decision Tree Classifier with PCA
4. logisticRegression.ipynb - Logistic Regression Classifier
5. logisticRegression_PCA.ipynb - Logistic Regression Classifier with PCA
6. randomForest.ipynb - Random Forest Classifier
7. randomForest_PCA - Random Forest Classifier with PCA
8. multiLayerPerceptron.ipynb - Multi-layer Perceptron Classification
9. multiLayerPerceptron_PCA.ipynb - Multi-layer Perceptron Classification with PCA

## Data Preprocessing

The file preprocess.ipynb is used for data preprocessing. The file saves the datasets in a `.pkl` file in the directory.<br>
The number of features after preprocessing is 168

## Models

All the models contain two approaches:
1. We use the 168 feature original data set to run the model.
2. We apply PCA on the original features,reduce them to 24 features and then run the models.<br>
All `_PCA` files are for the second approch.

`data_loader.py`is a data loading module for the dataset. The dataset has to be downloaded for it to work. (link above)

Keras and Scikitlearn are used in this project

### Project By:
 Ojas Parag Nadkar (44648846)
 Abhijeet Suresh Bhute (81004607)

