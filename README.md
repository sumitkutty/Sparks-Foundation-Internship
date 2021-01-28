# Sparks-Foundation-Internship
### These projects are a part of the internship by The Sparks Foundation
#### Basic implementation of some machine learning algorithms.


## Project 1
#### Objective:
* Exploratory data analysis on the global terrorism dataset. This project involved creating multiple graphs while deriving elborative insights to find hot spots and other security issues. 
* link: https://github.com/sumitkutty/Terrorism-Analysis
<br/> 
<br/>

## Project 2: Prediction using Supervised ML. 
### Objective:
* This project involved predicting the score of a student gives the number of hours studied. This is simple linear regression problem with one dependant and independant variable. The objective also included finding the score for 9.25 hrs/day study. The evaluations were done using k-cross validation (5 folds).

### Packages:
* Scikit-Learn, Pandas, Numpy, Matplotlib, Seaborn.
* Metrics Used: R-Squared Score,Mean Squared Error, Mean Absolute Error, Root Mean Squared Error. <br/>

### Evaluation:
* Average r2 score:  0.9180771341891051<br/>
* Average MAE score:  -5.701180786326049<br/>
* Average MSE score:  -38.4709444297968<br/>
* Average RMSE score:  -5.970137529278324<br/>
<br/>
<br/>

## Project 3: Prediction using Unsupervised ML.

### Data: Iris Dataset

### Objectives:
* Involves paritioning the data into clusters with similar characteristics. The objective also involves finding the optimal no of clusters to partion the data into.

### Methods used:
1. Elbow Method:
* This method is used to find the no of clusters which would be optimum.
* It is a method used a find the elbow point in the graph where the wcss is plotted against different k values.
* WCSS(within cluster sum of squares) is the avg distance between the datapoints and their respective centroids.
* so by definition, lower the WCSS, closer the datapoints are to their to centroids, better the clustering.

2. KMeans Algorithm:
* Kmeans is an unsupervised learning method which partitions the data into k clusters based on the data's characters.
* k value here is the value found by the elbow method. 

### Packages Used:
* Numpy, Pandas, matplotlib, seaborn, scikit-learn

### Evaluation:
* WCSS value: 78.94

<br/>
<br/>

## Project 4: Prediction using Decision Tree Algorithm

### Data: Iris Dataset

### Objectives: 
* The objective of the project was to construct a decision tree and visualize it.
* The decision tree classifier should be able to classify a custom data point.
* Visualizing the tree graphically.

### Methods:
1. EDA:
* Plotted a number of graphs denoting the distributions and the relations between the features

2. Cross Validation:
* Performed cross validation with 5 folds to test the accuracy of the classifier.

3. Hyperparameter Tuning:
* Tuned the model to find the optimum hyperparameters.

4. Modelling:
* Fit the optimal hyperparameters found on the test set.

5. Tree plot
* Plotted the tree using the plot_tree function from the tree class.

### Evaluation:
* Accuracy before tuning (cross validation): 0.94
* Accuracy after tuning: 0.9733
* Accuracy on the test set: 1.0
<br/>
<br/>

## THE END






