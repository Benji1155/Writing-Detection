
![Writing Detection](https://i.imgur.com/A4NquyT.png)

# Writing Detection

[![GitHub release (latest by date including pre-releases)](https://img.shields.io/github/v/release/Benji1155/Writing-Detection)](https://img.shields.io/github/v/release/Benji1155/Writing-Detection)
[![GitHub last commit](https://img.shields.io/github/last-commit/Benji1155/Writing-Detection)](https://img.shields.io/github/last-commit/Benji1155/Writing-Detection)
[![GitHub issues](https://img.shields.io/github/issues-raw/Benji1155/Writing-Detection)](https://img.shields.io/github/issues-raw/Benji1155/Writing-Detection)
[![GitHub pull requests](https://img.shields.io/github/issues-pr/Benji1155/Writing-Detection)](https://img.shields.io/github/issues-pr/Benji1155/Writing-Detection)
[![GitHub](https://img.shields.io/github/license/Benji1155/Writing-Detection)](https://img.shields.io/github/license/Benji1155/Writing-Detection)

**Brief Overview / Abstract

Introduction and Background**

This project focuses on identifying hand-drawn English letters to assist Korean speakers in learning the English alphabet. The project features a paint-style application where users can draw letters, and the model predicts the character. This tool is limited to single character recognition, not full words. To train the model, I used a dataset sourced from Kaggle, and the data was divided into training, testing, and validation sets.

**Images**

![K-Longo](https://i.imgur.com/pA0MkXC.png)

![K-Longo](https://i.imgur.com/geT7n85.png)

**Methodology**

To build the letter recognition model, I used a Convolutional Neural Network (CNN) with approximately 9 layers. The dataset was enhanced using ImageDataGenerator to improve the robustness of the model by augmenting the available data.
Tools and Techniques

The project was developed using Python, with Jupyter Notebook as the chosen IDE. For training the CNN model, I utilized TensorFlow.
Results and Evaluation

- After training the model for 10 epochs, I achieved an accuracy of 75%.
- With 100 epochs, the accuracy improved to 80%.

While this is a positive result, it wasn't as high as expected, primarily due to the small and sometimes inaccurate training dataset. However, the accuracy continued to rise with additional epochs, suggesting that with more data or longer training, the accuracy could improve further.

**Discussion and Conclusions**

In conclusion, the project implements a user-friendly GUI for easy input of drawn letters. A random letter generator feature provides practice for users with all available characters. A confidence score is displayed to indicate the model's certainty in its predictions. The CNN model, trained with 9 layers and using 10-100 epochs, performs well, with the application correctly identifying most of the drawn letters. The accuracy achieved shows promise, and with further training or data, the model could achieve even higher accuracy.
