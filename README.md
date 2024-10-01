# CIFAR-100-Image-Classification-Models

This project was part of the course work for DS5220: Supervised Machine Learning at Northeastern University. The project involves the implementation and comparison of several supervised learning models on the CIFAR-100 dataset, focusing on enhancing model performance through feature extraction, dimensionality reduction, and regularization techniques.

## Project Overview

In this project, the following machine learning models were applied on the CIFAR-100 dataset to analyze their performance and improve classification accuracy:

	1.	Support Vector Machine (SVM) without kernel
	2.	SVM with Radial Bias Function (RBF) kernel
	3.	Logistic Regression
	4.	Convolutional Neural Networks (CNN)

I processed and normalized the CIFAR-100 dataset, explored dimensionality reduction techniques like Principal Component Analysis (PCA), and experimented with feature extraction using ResNet model weights.


## Methodologies

	• Data Preprocessing:
	• The images (32x32x3) were normalized to a standard scale of 0.5x0.5x0.5 for optimal model performance.
	• Model Implementations:
	• SVM (without kernel): Initial accuracy of 13.42%.
	• Kernel SVM: Improved accuracy to 26.39%.
	• Logistic Regression: Achieved an accuracy of 27%.
	• Convolutional Neural Networks (CNN): Initial accuracies of up to 60% without regularization.


## Accuracy Graphs:

Below are the accuracy graphs for the models trained on CIFAR-100:

**SVM Without Kernel**

**SVM With RBF Kernel**

**Logistic Regression**

**Convolutional Neural Network**

	• **For 100 Classes without Regularization:**

 	• **For 20 Superclasses with Regularization:**

## PCA for Dimensionality Reduction

From the PCA analysis, I concluded that 50 components were sufficient to capture 80% of the variance in the dataset, improving model efficiency.
<img width="589" alt="Screenshot 2024-10-01 at 8 39 42 AM" src="https://github.com/user-attachments/assets/07eb7b88-bac5-43b4-bda8-d1d7874a1876">


## Feature Extraction and L2 Regularization

I applied feature extraction using pre-trained ResNet weights and introduced L2 regularization to improve performance, achieving the best results with CNN on the 20 superclass dataset with 82% accuracy.

## Conclusion

This project demonstrates the importance of feature extraction, dimensionality reduction, and regularization in improving supervised learning model performance on complex datasets like CIFAR-100. Kernel SVM and CNNs with superclass classification provided the best accuracy.
