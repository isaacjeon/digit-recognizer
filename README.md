# digit-recognizer
Short Kaggle project for Digit Recognizer competition. This project uses the MNIST dataset containing handwritten digits, and aims to create a model that classifies digits correctly.

https://www.kaggle.com/competitions/digit-recognizer

I used the approach from Chapter 3 Exercise #2 of the following book:

Géron, A. (2019). Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow: Concepts, Tools, and Techniques for Building Intelligent Systems (2nd ed.). O'Reilly Media.

This approach involes first augmenting the data by adding shifted versions of each image to the training set, which may increase performance of the model.
Then, a KNN classifier is trained on this new augmented training dataset.
