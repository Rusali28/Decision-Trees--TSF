# Decision-Trees--The Sparks Foundation

This Decision Tree project has been made as part of my Data Science and Business Analytics Internship at The Sparks Foundation (TSF).

## DECISION TREES
It is a supervised machine learning algorithm, which can be used for both classification as well as regression. In this project, we will be using Decision Trees as a classifier.

The goal of this algorithm is to create a model that predicts the value of a target variable, for which the decision tree uses the tree representation to solve the problem. The leaf node corresponds to a class label and attributes are represented on the internal node of the tree.

Leaf node refers to a node with zero children.

Internal nodes refer to nodes with children.

## DATASET
This is the first glimpse of the dataset.

![Dataset](https://github.com/Rusali28/Decision-Trees--TSF/blob/main/Images/dataset.PNG)



After importing the dataset, we visualise it using a pairplot, below is how the visualisation appears.


## Pairplot
![PairPlot](https://github.com/Rusali28/Decision-Trees--TSF/blob/main/Images/Pairplot.PNG)

Pairplots can be very useful to understand all possible relationships between all the features in our dataset. From this above pairplot, we can see that the clusters of Species
'versicolor' and 'virginica' are closely related, whereas 'sertosa' is more distinct.


## We create a few more plots to understand the distribution of data
## BOXPLOT
![Boxplot](https://github.com/Rusali28/Decision-Trees--TSF/blob/main/Images/boxplot.PNG)

## BOX_AND_STRIPPLOT
![boxstrip](https://github.com/Rusali28/Decision-Trees--TSF/blob/main/Images/box_stripplot.PNG)


We can plot box plots using a categorical feature against a continuous feature, to understand how our data is distributed over the different features. Here, we have combined a
stripplot to identify visible number of outliers also.

## JOINTPLOT
![joint](https://github.com/Rusali28/Decision-Trees--TSF/blob/main/Images/hex_jointplot.PNG)

From the above jointplot, we can find the major areas of concentration of our data points, the darker hexagons refer to higher concentration, lighter hexagons refer to lesser
concentration.


In order to make a classification model, we take the **Species** column as our target. We encode the Species data using LabelEncoder and below are the labels.


From the dataset, we have three species of the Iris flower, alongwith the labels:
+ Iris-setosa      -  0
+ Iris-versicolor  -  1
+ Iris-virginica   -  2

Here is a picture of the final dataset, after encoding the Species column and shuffling the dataset for uniform splitting of train and test data.

![Final_Data](https://github.com/Rusali28/Decision-Trees--TSF/blob/main/Images/final%20dataset.PNG)


Hereafter, we train and test our decision tree and here is the visualization of the final decision tree using Graphviz.

![Graphviz](https://github.com/Rusali28/Decision-Trees--TSF/blob/main/Images/visual-graphviz.PNG)






### Guidelines to use the repo:
- Cloning the Repository: 

        git clone https://github.com/Rusali28/Decision-Trees--TSF.git
        
- Entering the directory: 

        cd Decision-Trees--TSF


