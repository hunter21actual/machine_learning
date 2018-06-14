The Iris Flowers Dataset involves predicting the flower species given measurements of iris flowers.

It is a multi-class classification problem. The number of observations for each class is balanced. There are 150 observations with 4 input variables and 1 output variable. The variable names are as follows:

    1. Sepal length in cm.
    2. Sepal width in cm.
    3. Petal length in cm.
    4. Petal width in cm.
    5. Class (Iris Setosa, Iris Versicolour, Iris Virginica).

The baseline performance of predicting the most prevalent class is a classification accuracy of approximately 26%.

The dataset as well as information above was taken from Dr. Jason Brownlee's site:- 
    https://machinelearningmastery.com/standard-machine-learning-datasets/
 
Multiple classification Algorithms were applied on the dataset.
Some terms:- 
LDA - Linear Discriminant Analysis
KNN - K Nearest Neighbours
RBF - Radial Basis Function

The results are as follows:

        Algorithm                     Accuracy(in %)
        
1. Linear SVM without LDA                 86.84
2. Linear SVM with LDA                    92.10
3. Kernal SVM with RBF kernel             86.84
4. K Nearest Neighbours                   89.47
5. Logistic Regression                    86.84
6. Naive Bayes                            94.73
7. Random Forest                          84.21
