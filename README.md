# MNIST-Digit-Recognition-using-SVM
Project Description:
This project implements a handwritten digit recognition system using a Support Vector Machine (SVM). SVM is a powerful supervised learning algorithm commonly used for classification tasks, including image recognition.

Dataset Used:
The project uses a well-known dataset of handwritten digits:

Training Set: A large collection of images used to train the SVM model.
Test Set: A separate set of images for evaluating the model's performance.
Image Details: Each image is 28x28 pixels in grayscale.
Model Used:The Support Vector Machine (SVM) is used for classification. Key aspects include:

Kernel: The kernel function used for the SVM is selected based on the data's characteristics to transform the input space into a higher-dimensional space where a hyperplane can be used for separation.
Regularization: The regularization parameter helps balance the trade-off between achieving a low error on the training data and minimizing the model complexity to prevent overfitting.

Multi-class Classification: SVM inherently handles binary classification; for multi-class tasks like digit recognition, techniques such as one-vs-one or one-vs-all are used.

Training:
Optimization: The SVM optimizes the margin between different classes.
Hyperparameter Tuning: Parameters like the kernel type and regularization parameter are tuned to achieve the best performance.
Evaluation Metrics: Accuracy and confusion matrix are used to evaluate the SVM's performance.

Results:
The SVM model achieves a high level of accuracy on the test set, showcasing its effectiveness in classifying handwritten digits.
Visualization of the confusion matrix and misclassified examples helps to understand the model's performance and areas for improvement.
