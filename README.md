

## X-Ray Image Classification for Body Parts

This project is part of my coursework for the Computer Vision and Machine Learning module.

The aim is to build a comparative experimental validation framework to test different machine learning algorithms for classifying X-ray images from different body sections.

### Dataset

I collected a dataset of 3,615 X-ray images from three different repositories. The dataset includes X-ray images of 'hands', 'shoulders', and 'chests'. It is intentionally imbalanced for the purpose of this coursework.

## Data Collection Requirements

 - At least 500 images per class.
 - Grayscale image format.
 - Images are stored in commonly used formats such as JPEG, PNG, etc.

### Experiments

Four experiments were conducted to validate the models:

1. *Neural Network with Unaltered Training Data*: Used a neural network-based machine learning architecture without any alteration in the training dataset.
2. *Balanced Training Data with Neural Network*: Balanced the classes in the training data using image augmentation and used a neural network-based architecture.
3. *Feature Extraction with Various Classifiers*: Utilized feature extraction techniques like Harris, SIFT, SURF, HOG, etc., and tested with multiple machine learning architectures.
4. *Feature Extraction with Balanced Training Data*: Used feature extraction combined with data balancing techniques like random undersampling, and applied various machine learning models including NN.

### Metrics
    
     - Precision
     - Recall
     - F1-score
     - Confusion Matrix
     - ROC AUC


### Results
§
Results and comparisons between the experiments are presented in tables and plots in the notebook.

### Future Work

The project is open to further improvements including but not limited to employing more advanced machine learning techniques, using larger datasets, and fine-tuning the existing models.

### Technologies Used

     - Python
     - CNN (Convolutional Neural Networks)
     - Image Augmentation
     - Random Undersampling
     - Neural Networks


### Feel free to check out the notebook for a more in-depth explanation and code details.
