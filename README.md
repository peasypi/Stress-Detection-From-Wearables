# Stress-Detection-From-Wearables

Repository of the 'stress detection from wearables'-task for the module 'Big Data Praktikum'.
The task is to detect the stress level of a person based on the data of the wearable sensors (e.g. heart rate, accelerometer, etc.). To be more specific we are looking for commercial wearables as smartwatches.

The [`WESAD-Dataset`](https://dl.acm.org/doi/10.1145/3242969.3242985) is used to train and evaluate the model.

We trained two different models to detect the stress level on the WESAD dataset:
- A [`CNN-model`](https://github.com/peasypi/Stress-Detection-From-Wearables/blob/main/code/cnn.ipynb) based on the work of Gil-Martin et al. [`Human Stress Detection with Wearable Sensors Using Convolutional Neural Networks`](https://ieeexplore.ieee.org/document/9669993)
- A [`LDA-classifier`](https://github.com/peasypi/Stress-Detection-From-Wearables/blob/main/code/lda.ipynb) based on the work of Siirtola [`Continuous stress detection using the sensors of commercial smartwatch`](https://dl.acm.org/doi/10.1145/3341162.3344831)

