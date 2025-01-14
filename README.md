# CIFAR-10 overlap separation

This UniBo project involves training a neural network on the CIFAR-10 dataset using TensorFlow and Keras. The model leverages data augmentation techniques to improve accuracy and generalization, and implements Learning Rate Scheduling.

## Features
- **Dataset**: CIFAR-10, consisting of 60,000 32x32 color images across 10 classes.
- **Data Augmentation**: Includes random flips, rotations, and brightness adjustments to enhance the training dataset.
- **Model Architecture**: A convolutional neural network (CNN) with separate heads for classifying grouped labels.
- **Evaluation**: Measures accuracy for two separate groups of classes and provides overall average accuracy. Evaluation is then executed 10 times to assess Standard Deviation.

## How to Use
1. Open the notebook in [Google Colab](https://colab.research.google.com/).
or
2. Clone this repository to Colab:
   ```bash
   git clone https://github.com/<username>/<repository>.git
   ```
3. Run the notebook to:
   - Train the model on the CIFAR-10 dataset.
   - Evaluate the model on test data.
   - Experiment with different data augmentation techniques.

## Requirements
- Python 3.7+
- TensorFlow 2.x
- NumPy
- Matplotlib
