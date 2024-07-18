# ComputerVision-Image-Classification
Classifies different digit images and butterfly images with scikit-learn, numpy

Digit images retrieved from MNIST dataset
Butterfly images retrieved from Leeds butterfly dataset

Model design:
1. Extract feature from images
2. Train classifier on features

MNIST (digit images) dataset:
- Convert raw images into 1D vector
- Learn LDA transformation from vectors

Leeds butterfly (butterfly images) dataset:
- Compute and extract key components and features from grayscale images of the butterflies
- Learn LDA transformation to extract features

Comparing 3 classifiers: Logistic Regression, Multi Layer Perceptron, and AdaBoosted Decision Trees




# Classification labels (species):
<img width="878" alt="species" src="https://github.com/user-attachments/assets/81fdbb7e-29ee-4031-9b7b-8b3cb130ce87">

# Analysis of classifiers:
- AdaBoosted decision tree: high training accuracy and low validation accuracy, Multi layer perceptron: does better overall
- AdaBoosted has overfit training data, Multi layer perceptron has complex neural network

  
![image](https://github.com/user-attachments/assets/d4614401-9827-4244-801b-2cdcd0c5a953)

# Butterfly images classification results:
![image](https://github.com/user-attachments/assets/64626862-765c-4899-aebe-62c2262a098a)

