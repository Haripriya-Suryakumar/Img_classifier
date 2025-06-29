# Cat vs Dog Image Classifier (CNN using TensorFlow & Keras)

This project implements a Convolutional Neural Network (CNN) to classify images of cats and dogs. It was developed and trained in Google Colaboratory using TensorFlow and Keras.
---
## Dataset

The dataset was provided by freeCodeCamp and downloaded using:
wget https://cdn.freecodecamp.org/project-data/cats-and-dogs/cats_and_dogs.zip

- 2000 training images (1000 cats, 1000 dogs)  
- 1000 validation images (500 cats, 500 dogs)  
- 50 test images (unlabeled, used for prediction)
---
## Model Architecture

The model was built using Keras Sequential API and includes:

- 4 convolutional layers (Conv2D) with ReLU activations
- MaxPooling2D layers after each convolution
- Flattening and Dropout
- Fully connected Dense layer with 512 units
- Final Dense layer with sigmoid activation for binary classification

The model uses:

- Binary cross-entropy loss
- Adam optimizer
- Accuracy as the evaluation metric
- Trained for 15 epochs
---
## Results
The model achieved over 63% validation accuracy, passing the official challenge requirement.
---
## Technologies Used

- Python 3
- TensorFlow 2.x
- Keras
- Google Colab
- Matplotlib (for data visualization)
