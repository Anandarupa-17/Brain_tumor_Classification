# CNN Brain Tumor Classification
Overview
This project aims to classify brain tumors into four types: glioma tumor, meningioma tumor, pituitary tumor, and no tumor using Convolutional Neural Networks (CNNs). The CNN model is trained on a dataset containing Magnetic Resonance Imaging (MRI) scans of brain tumors.

# Dataset
The dataset used in this project consists of MRI images of brain tumors, labeled with one of the following classes:

1.Glioma tumor
2.Meningioma tumor
3.Pituitary tumor
4.No tumor

Each MRI image is represented as a matrix of pixel values, with dimensions corresponding to the size of the image.

# Model
The CNN model is implemented using TensorFlow and Keras. The model architecture consists of multiple convolutional layers followed by max-pooling layers to extract features from the MRI images. The extracted features are then passed through one or more fully connected layers for classification.

# Preprocessing
Before training the CNN model, the MRI images undergo preprocessing steps, including:

1.Resizing: The images are resized to a standard size suitable for input to the CNN model.
Normalization: The pixel values of the images are normalized to a range between 0 and 1 to facilitate model training.
2.Data augmentation: Techniques such as rotation, flipping, and zooming may be applied to augment the dataset and improve the generalization ability of the model.

# Training
The CNN model is trained on the preprocessed MRI images. The dataset is split into training and testing sets to evaluate the model's performance. The model is trained using backpropagation and optimized using the Adam optimizer. The accuracy of the model on the training and testing sets is monitored during training.

# Evaluation
The performance of the CNN model is evaluated using metrics such as accuracy, precision, recall, and F1-score on the testing set. The accuracy of the model is **90%**, indicating its effectiveness in classifying brain tumors.

Additionally, visualizations such as confusion matrices and classification reports may be generated to assess the model's performance across different classes.

# Usage
To use the CNN model for brain tumor classification:

Install the required dependencies (TensorFlow, Keras, etc.).
Load the MRI images of brain tumors.
Preprocess the images (resizing, normalization, etc.).
Train the CNN model on the preprocessed images.
Evaluate the model's performance using suitable metrics.
Make predictions on new MRI images using the trained model.
