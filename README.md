# study

from tensorflow.keras.datasets import mnist
import matplotlib.pyplot as plt

# MNIST dataset ачааллах
(x_train, y_train), (x_test, y_test) = mnist.load_data()

print(x_train.shape)  # (60000, 28, 28) гэж гарах ёстой