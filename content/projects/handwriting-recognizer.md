---
title: 'Handwriting Recognizer'
disableshare: true
summary: 
draft: false
hidemeta: false
weight: 9
---

This project involves the implementation of a handwriting recognition system using a Convolutional Neural Network (CNN). The system reads images using the `opencv-python` library and utilizes a model defined in the following code:

## Data Preprocessing

The dataset is preprocessed by splitting it into training and testing sets. The images are reshaped to a size of 28x28 pixels, and the corresponding labels are one-hot encoded.

## Convolutional Neural Network Model

The CNN model is defined with three convolutional layers followed by max-pooling layers. It concludes with fully connected layers for classification.

## Model Training

The model is compiled using the Adam optimizer and categorical crossentropy loss. Training is performed for a specified number of epochs.

## Command Line Interface (CLI)

The project includes a CLI for convenient interaction. The CLI usage is stated below:

`python recog.py [options]`

### Options

`--aloud`: Outputs recognized words in speech form.  
`--show-input`: Displays processed input image.  
`--show-sample-data`: Displays sample dataset images.  

## Technologies Used

- **OpenCV-Python**: For reading and processing images.
- **Matplotlib**: For visualizing data and images.
- **NumPy**: For numerical operations on data.
- **Keras**: For building and training the CNN model.
- **TensorFlow**: As the backend for Keras.
- **Click**: For creating a Command Line Interface (CLI).

## Related Links

- [GitHub Repository](https://github.com/vishruthdevan/handwriting-recognizer/)
