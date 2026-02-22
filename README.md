# 🏞️ Intel Scene Classifier

This repository contains a Jupyter Notebook for building and training a **Convolutional Neural Network (CNN)** capable of accurately classifying images of natural scenes.

##  Target Classes
The model is trained to recognize and classify images into one of the following 6 categories:
1. Mountain
2. Sea
3. Street
4. Glacier
5. Forest
6. Building

##  Features & Project Breakdown

1. **Data Exploration & Visualization**
   - Displaying sample images from each class to understand the structure, variety, and distribution of the dataset.

2. **Data Preprocessing**
   - Utilizing `ImageDataGenerator` to efficiently load, preprocess, and augment the image data for training and testing.

3. **CNN Architecture**
   - Building a Sequential model that combines:
     - **Conv2D layers** for extracting visual features from the images.
     - **MaxPooling2D layers** for spatial dimensionality reduction.
     - **Dropout layers** for regularization to prevent overfitting.
     - **Dense (Fully Connected) layers** to output the final classification probabilities.

4. **Training & Evaluation**
   - Training the neural network while implementing **Early Stopping** to monitor validation loss, ensuring optimal accuracy and avoiding over-training.
   - Evaluating the model's performance and making predictions on unseen test images.

##  Requirements & Libraries

This project primarily relies on the TensorFlow framework. To run the notebook, ensure you have the following libraries installed:
- `numpy`
- `matplotlib`
- `tensorflow` / `keras`

You can install the required dependencies using:
```bash
pip install numpy matplotlib tensorflow
