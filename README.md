# dog-breed-multi-class-classification

## End-to-End Multi-Class Dog Breed Classification
This project demonstrates building an end-to-end multi-class image classifier using TensorFlow 2.0 and TensorFlow Hub to identify the breed of a dog from an image.

### 1. Problem Definition
Can we build a machine learning model capable of identifying a dog's breed from its image?

### 2. Data
The dataset used is from Kaggle's Dog Breed Identification competition: https://www.kaggle.com/competitions/dog-breed-identification/overview 

It includes labeled training images and unlabeled test images.

###  3. Evaluation
Submissions are evaluated using Multi-Class Log Loss. The objective is to minimize the log loss between the predicted probabilities and the actual target labels for each test image.

For more details, see the competition evaluation page: https://www.kaggle.com/competitions/dog-breed-identification/overview

### 4. Features
Key characteristics of the dataset:

Type of data: Images (unstructured data), ideal for deep learning models.
Number of classes: 120 dog breeds.
Training set size: Over 10,000 labeled images.
Test set size: Over 10,000 unlabeled images.

### 5. Modeling
This project involves leveraging TensorFlow 2.0 and TensorFlow Hub to build a multi-class image classification model. The focus is on implementing an efficient deep learning pipeline to achieve high accuracy in predicting dog breeds.
