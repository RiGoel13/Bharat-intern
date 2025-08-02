# MNIST Handwritten Digit Classification

This project illustrates a basic neural network with TensorFlow and Keras to classify handwritten digits from the MNIST dataset. It trains a model to identify digits (0-9) from grayscale 28x28 pixel images.

## Dataset

The MNIST dataset is a popular benchmark for handwritten digit classification. It has 60,000 training images and 10,000 test images, each labeled with the corresponding digit.

## Prerequisites

* Python 3.8+
* TensorFlow 2.13+
* Keras (within TensorFlow)

Install the necessary packages:

```bash
pip install tensorflow
```

## Project Files

* `mnist_classification.py`: Primary code file for model training and testing.
* `README.md`: This documentation file.

## Usage

1. Download the repository or project files using clone.
2. Execute the training script:

```bash
python mnist_classification.py
```

3. The script will:

   * Load and process the MNIST dataset
   * Construct a neural network model
   * Train the model for 5 epochs
* Train the model on the training set

## Expected Output

```
Epoch 1/5
1875/1875 [==============================] - 9s 5ms/step - loss: 0.0685 - accuracy: 0.9779
Epoch 2/5
1875/1875 [==============================] - 9s 5ms/step - loss: 0.0588 - accuracy: 0.9809
.
Epoch 5/5
1875/1875 [==============================] - 9s 5ms/step - loss: 0.0447 - accuracy: 0.9850
Test accuracy: 0.9770
```

## Model Architecture

* Flatten Layer (input: 28x28, output: 784)
* Dense Layer (128 units, ReLU activation)
* Dropout Layer (20% dropout)
* Dense Layer (10 units, Softmax activation)

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contributing

It's okay to fork the repository and make pull requests if you have suggestions or extra features to implement.

## Contact

For questions or feedback, contact the project maintainer.

