# Prediction-of-covid-19-using-chest-X-ray-images

Data taken from- https://github.com/RishitToteja/Chext-X-ray-Images-Data-Set.git

In this project, Built and trained a convolutional neural network in Keras with TensorFlow as backend from scratch to predict patients if they were infected with COVID-19 or not using their chest X-ray images. Matplotlib was used for data visualization. Data preprocessing and data augmentation was carried out using tensorflow 2.0 The model used was sequential with a combination of convolutional layers, pooling layers, dropout layers, dense layers with relu activation and output layer with sigmoid activation. The dataset contained the lungs X-ray images of both groups i.e non-covid and covid infected patients. The dataset was obtained from kaggle. Metrics chosen for model evaluation were Training set, test set and validation set accuracy. Adam optimizer with learning rate of 0.001 was choosed for gradient descent The entire project was carried out on the Google Colab environment Results of the model were following:

Training Set Accuracy : 97.38 %

Training Set Loss : 0.0875

Validation Set Accuracy : 97.79 %

Validation Set Loss: 0.0744

Test Set Accuracy : 98.14 %

Test Set Loss : 0.06641
