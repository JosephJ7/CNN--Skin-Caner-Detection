# CNN--Skin-Caner-Detection

# Project👌 
On the given dataset we need to detect 2 different classes of moles using Convolution Neural Network with keras tensorflow in the backend and then analyze the result to see how different models can be useful in practical scenarios.
Deep Learning Algorithm - InceptionV3,Sequential modeling,MobileNetV2,VGG6

## Description of dataset 🤖 - Kaggle 
The dataset was obtained from the International Skin Image Collaboration (ISIC) Archive. It includes 1800 images of benign moles and 1497 images of malignant categorised moles. All of the images have been downsized to 224x224x3 RGB (low resolution).
The images are initially divided for training and testing purposes.
There are two types of skin cancer, which are stated below:
1. Benign
2. Malignant

# Results 🥳
 Initially the dataset was split into train and test. The training dataset was divided into two categories, benign and malignant to train the models . Four models were selected: Sequential with <b> 85% </b>, VGG16, MobileNetV2 with <b> 76% </b> and InceptionV3 with <b> 83% </b>, out of which VGG16 gave the highest accuracy of <b> 86% </b>. Then after training, the test dataset was used. It took in consideration all the images consisting of benign and malignant moles. 50 epochs were run on train and test dataset to evaluate the loss, accuracy, val_loss and val_accuracy. Then a mole is selected to evaluate if it is benign or malignant.
