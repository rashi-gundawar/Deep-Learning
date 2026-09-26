# Assignment 03 – Forward and Backpropagation using TensorFlow/Keras

## Objective
To implement forward propagation and backpropagation using TensorFlow/Keras and analyze the effect of different learning rates and number of epochs on model performance.

## Dataset
**Fashion-MNIST Dataset**
The Fashion-MNIST dataset contains grayscale images of clothing and fashion items.
- Image Size: 28 × 28 pixels
- Number of Classes: 10
- Training Images: 60,000
- Testing Images: 10,000

## Tasks Performed
- Loaded the Fashion-MNIST dataset
- Reshaped the images into 784-element vectors
- Normalized pixel values from 0–255 to 0–1
- Built a neural network using TensorFlow/Keras
- Implemented forward and backpropagation through model training
- Compared different learning rates
- Compared different numbers of epochs
- Evaluated model performance on the test dataset
- Plotted Learning Rate vs Accuracy
- Plotted Epochs vs Accuracy
- Plotted Training vs Validation Accuracy
- Plotted Training vs Validation Loss
- Evaluated the final model

## Learning Rate Comparison
The following learning rates were compared:
- 0.1
- 0.01
- 0.001
Each model was trained for 5 epochs and its test accuracy was recorded.

## Epoch Comparison
The following numbers of epochs were compared:
- 5
- 10
- 20
The learning rate was kept at `0.001`.

## Evaluation
The model was evaluated using:
- Test Loss
- Test Accuracy
- Training Accuracy
- Validation Accuracy
- Training Loss
- Validation Loss

## Tools and Technologies
- Python
- Google Colab
- TensorFlow
- Keras
- NumPy
- Pandas
- Matplotlib
- 
## Result
The effect of different learning rates and training epochs on the neural network performance was analyzed. The final model was trained with a learning rate of `0.001` for `20` epochs and evaluated on the Fashion-MNIST test dataset.
