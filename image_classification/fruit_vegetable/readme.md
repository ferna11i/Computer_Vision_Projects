# Fruit and Vegetable -360 image classification


In this project a simple ResNet-50 model was trained on 52208 images 
of fruits and vegetable images to classify an image into one of 
131 classes. The dataset is available on Kaggle at [link](https://www.kaggle.com/moltean/fruits).
This code was developed in PyTorch while the weights were extracted from Detectron2.

By training the model for 3 epochs, it can achieve 99% recall and precision.


The *Fruit_Vegetable_classification.ipynb* file contains the code for 
1. Data cleanup and generating csv files for Train, Test and Validation data.
2. To train a ResNet-50 model for three epochs and test the recall and precision
of the model.


*Note: This code was developed on Google Colab Pro*

Future works: Test the trained model on unseen data from other data sets

