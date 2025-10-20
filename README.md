iris-classification-ml

a machine learning project on the iris dataset. 
the dataset has 150 samples of iris flowers divided into 3 species: setosa, versicolor and virginica. 

each sample has 4 features: sepal length, sepal width, petal length and petal width. 

the goal is to predict the species based on these features.

models implemented:

- decision tree classifier
- logistic regression (multiclass)
- k-nearest neighbors (knn)
- support vector machine (svm)
- more soon...

evaluation:

- for each model ill check accuracy on the test set
- confusion matrix to see misclassifications
- precision, recall and f1 score per class
- cross validation for k selection in knn and general robustness check
- visualize decision boundaries for 2d feature slices where possible
