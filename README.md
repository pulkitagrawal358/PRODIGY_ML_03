Cat vs Dog Image Classification using SVM

This project implements a Support Vector Machine (SVM) to classify images as either a "Cat" or a "Dog".

Overview
Dataset: Microsoft Cats vs Dogs Dataset from Kaggle.
Algorithm: Support Vector Machine (SVM).
Feature Extraction: Histogram of Oriented Gradients (HOG).
Environment: Google Colab.

Methodology
SVMs cannot process raw images efficiently. To solve this, the project uses HOG to extract the "structure" and "edges" of the animals.
Preprocessing: Images are converted to grayscale and resized to 64x64 pixels.
Feature Extraction: HOG descriptors are calculated for each image to capture shapes.
Training: An SVM model is trained on these descriptors to learn the difference between cats and dogs.

Results
The model achieved an accuracy of 74.67% on the test set.
Class  Precision  Recall  F1-Score
Cat    0.77       0.74    0.75
Dog    0.73       0.75    0.74

How to Run
Clone this repository.
Open the .ipynb file in Google Colab.
Follow the instructions in the notebook to set up your Kaggle API Key and download the dataset.
Run all cells to train and evaluate the model.


Note:
The dataset is not included in this repository due to its large size.
Please download it directly from Kaggle.
