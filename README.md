MNIST Handwritten Digit Classification Using Deep Learning

Overview:

This project demonstrates the power of Deep Learning in classifying handwritten digits from the MNIST dataset. By implementing a simple Neural Network (NN), the model achieves an impressive accuracy of 96%. The project includes essential steps like Exploratory Data Analysis (EDA), data preprocessing, and visualizations (e.g., confusion matrix) to better understand and evaluate the model's performance.

Dataset:

The dataset used in this project is the well-known MNIST dataset, which contains 60,000 training images and 10,000 testing images of handwritten digits (0-9). It is loaded directly using TensorFlow/Keras:

Project Structure:

Exploratory Data Analysis (EDA):

  Analyzed sample digit images and their pixel distributions.
  Visualized a few sample digits for better understanding of the dataset.

Data Preprocessing:

  Normalized the pixel values to range between 0 and 1.
  Flattened the input images to make them compatible with the neural network input layer.

Modeling:

  Built a Neural Network with an input layer, multiple hidden layers, and a softmax output layer.

Training:

  The model was trained using categorical crossentropy loss and the Adam optimizer, achieving an accuracy of     98% on the test set.

Evaluation:

  A confusion matrix was generated to visualize the performance of the model on the test set.

Prediction:

  The trained model was used to make predictions on new samples and accurately classify the digits.

Results Summary

The neural network model was able to achieve the following results:

Metric--> Value

Accuracy:	98%
Loss:  0.0346 
