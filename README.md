
# Retinal Disease Classification using Deep Learning

## Overview

This project aims to develop a deep learning-based model to classify retinal fundus images into four categories: **Cataract, Glaucoma, Diabetic Retinopathy, and Normal.** The model leverages Convolutional Neural Networks (CNNs) and transfer learning techniques to assist in automated diagnosis of retinal diseases. The project demonstrates the potential of AI in healthcare by enabling faster and more accurate disease detection from retinal images.


## Objectives

* To implement a CNN-based deep learning model for retinal disease classification.
* To preprocess and augment retinal fundus images for better model performance.
* To train and evaluate the model using publicly available datasets.
* To analyze the performance of the model through accuracy, precision, recall, and F1-score metrics.
  

## Dataset

The dataset used in this project is the **Eye Diseases Classification Dataset** available on [Kaggle](https://www.kaggle.com/datasets/gunavenkatdoddi/eye-diseases-classification).
It consists of thousands of retinal fundus images categorized into four disease classes:

* Cataract
* Glaucoma
* Diabetic Retinopathy
* Normal


## Methodology

1. **Data Collection:** Dataset sourced from Kaggle.
2. **Data Preprocessing:** Image resizing, normalization, and label encoding.
3. **Data Augmentation:** Techniques like rotation, flipping, zooming, and brightness variation to prevent overfitting.
4. **Model Architecture:** A CNN-based model designed using TensorFlow and Keras.
5. **Training & Validation:** Model trained for 32 epochs with Adam optimizer and categorical cross-entropy loss.
6. **Evaluation:** Metrics such as accuracy, precision, recall, F1-score, and confusion matrix used for evaluation.


## Implementation Details

* **Programming Language:** Python
* **Environment:** Jupyter Notebook (Anaconda)
* **Frameworks/Libraries:**

  * TensorFlow / Keras
  * NumPy, Pandas
  * Matplotlib, Seaborn
  * Scikit-learn


## Results

* Achieved **89% classification accuracy** on the validation dataset.
* High precision and recall across all classes.
* The confusion matrix confirmed strong classification performance for all categories.


## Future Scope

* Implement explainable AI (XAI) techniques for visual interpretation of CNN outputs.
* Extend the model for real-time screening through a web or mobile application.
* Integrate with cloud-based healthcare systems for large-scale deployment.

