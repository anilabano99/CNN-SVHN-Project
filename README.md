Title: Street View Housing Number Digit Recognition
Objective:
The objective of this project is to develop a Convolutional Neural Network (CNN) model capable of accurately recognizing digits from street view images. The model will be trained on the SVHN dataset, which consists of cropped images of house numbers from Google Street View.
Description:
This repository contains the Python code for training and evaluating a CNN model for street view housing number digit recognition. The code includes the following steps:
1.Data Import and Preprocessing:
oLoads the SVHN dataset from an h5 file.
oVisualizes the data distribution and sample images.
oNormalizes the pixel values and converts labels to categorical format.
2.CNN Model Creation:
oConstructs three different CNN architectures: 
Primary Model: A basic CNN with convolutional, pooling, and dense layers.
Model1: Similar to the primary model but with Batch Normalization layers.
Model2: Increases the number of convolutional layers and uses dropout for regularization.
3.Model Training and Evaluation:
oTrains each model using the training set and validates on the validation set.
oVisualizes the training and validation accuracy and loss curves.
oEvaluates the model's performance on the test set and visualizes predictions.
4.Best Model Analysis:
oCompares the performance of the three models and identifies the best one.
oVisualizes the accuracy and loss curves of the best model.
5.Model Saving and Loading:
oSaves the best model for future use.
oLoads the saved model and evaluates its performance on different datasets.
6.Confusion Matrix Analysis:
oGenerates a confusion matrix to assess the model's classification accuracy for each digit class.
oVisualizes the confusion matrix using a heatmap.
Conclusion:
The developed CNN model demonstrates promising performance in recognizing street view housing number digits. The best-performing model, Model2, achieves high accuracy on both the training and test sets. This model can be used as a valuable tool for applications such as automated house number extraction from street view images.
