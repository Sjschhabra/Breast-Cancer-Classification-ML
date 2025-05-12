# Breast Cancer Diagnosis using Machine Learning

This project focuses on diagnosing breast cancer using machine learning techniques applied to digitized images of FNA (Fine Needle Aspiration) samples. It utilizes a dataset consisting of 569 samples, each described by 30 features extracted from the images.

![Image](https://raw.githubusercontent.com/Sjschhabra/Breast-Cancer-Classification-ML/refs/heads/main/Screenshot%202025-05-11%20170010.png)
## Dataset

- Contains 569 samples with 30 features computed from digitized FNA images of breast masses.
- Features include mean, standard error, and worst values for attributes such as radius, texture, perimeter, area, smoothness, compactness, concavity, concave points, symmetry, and fractal dimension.

## Model Architecture

- Neural network model with four dense layers using ReLU activation functions.
- Compiled with the Adam optimizer and binary cross-entropy loss function.

## Training

- Data split into 80% training and 20% testing sets.
- Model trained for 100 epochs with a batch size of 32.

## Evaluation

- Model achieves an accuracy of approximately 95% on the test set, indicating its effectiveness in predicting breast cancer diagnosis.

## Conclusion

This project showcases the application of neural networks for breast cancer diagnosis using features extracted from FNA images. The trained model demonstrates promising performance and has the potential for further optimization and deployment in clinical settings.
