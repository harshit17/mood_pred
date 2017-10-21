# mood_pred
Predicting mood based upon extracted features
Features are extracted on the basis of pre defined action units like lip curling upward etc.
The diffrent algorithms applied until now are KNN classifer, and SVM classifier.
In knn, we created a dimensional vector as a feature vector for each test image and then extracted 5 nearest neighbours of the same. The majority label given by the neighbours is assigned as the class label for the test. Accuracy of around 45% was achieved.
In svm, we implemented the use of One VS rest method for classification of multi label classifiers. 
