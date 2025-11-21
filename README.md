📘 README — Task 6: K-Nearest Neighbors (KNN) Classification
🎯 Objective

The goal of this task is to implement the K-Nearest Neighbors (KNN) algorithm for a classification problem and understand how the choice of K affects performance.

🛠️ Tools & Libraries Used

Python

Scikit-learn — for KNN model and evaluation

Pandas — for data handling

Matplotlib — for data visualization

NumPy — for numerical operations

📚 Dataset

This project uses the Iris dataset (available in sklearn.datasets).
For visualizing decision boundaries, only the first two features are used.

🚀 Steps Performed
1️⃣ Load the dataset

The Iris dataset is loaded using load_iris().

Only the first two features are selected for easy visualization.

2️⃣ Normalize the features

Since KNN is distance-based, normalization is required.

StandardScaler is used to scale the data.

3️⃣ Split into training and testing sets

Dataset is split using:

train_test_split(test_size=0.3)

4️⃣ Train KNN using different K values

K values from 1 to 10 are tested.

Accuracy for each K is printed.

The best K value is automatically selected.

5️⃣ Train final KNN model

The model is retrained using the best K value.

6️⃣ Evaluate the model

Evaluation metrics used:

Accuracy Score

Confusion Matrix

7️⃣ Visualize Decision Boundary

A decision boundary plot is generated to show how the KNN classifier separates the classes.

Useful for understanding model behavior.

📊 Outputs You Will See

✔ Accuracy for different K values
✔ Best K value
✔ Final accuracy
✔ Confusion matrix
✔ Decision boundary plot

📝 Conclusion

K-Nearest Neighbors is a simple yet powerful classification algorithm.
This task helps you understand:

How K affects classification

Importance of normalization

Evaluating models using accuracy and confusion matrix

Visualizing decision boundaries
