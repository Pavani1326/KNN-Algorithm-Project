# KNN-Algorithm-Project
# Project Title:
Make the prediction for "iris.csv" using KNN algorithm of Machine Learning, to find the value of K for Supervised Learning Clustering.

# Project Statement:
A American based botnical garden a grow iris flower in their labs but using bio technology in a single tree different type of varitey flower is grow.As a DataScience Engineer find out how much accuracy is their all categorys contains same spieces

# Project Approach:
Train the classifier on the training data

knn_classifier.fit(X_train, y_train)

KNeighborsClassifier

KNeighborsClassifier(n_neighbors=3)

# Project Accuracy
 Calculate accuracy
accuracy = accuracy_score(y_test, y_pred)
print(f"Accuracy: {accuracy:.2f}")

Accuracy: 1.00


# Conclusion:
According to my KNN model the value of K=3 then my model is successfully implement
