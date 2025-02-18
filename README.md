# MELANOMA DETECTION
> Build a multiclass classification model using a custom convolutional neural network in TensorFlow.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## Background
Cancer encompasses over 200 distinct types, with melanoma being the deadliest form of skin cancer. The diagnostic process for melanoma typically begins with clinical screening, followed by dermoscopic analysis and histopathological examination. Early detection is crucial, as it significantly improves the likelihood of successful treatment. The initial diagnosis involves a visual examination of the affected skin area. Dermatologists use high-speed cameras to capture dermatoscopic images of skin lesions, achieving diagnostic accuracies between 65% and 80% without additional technical support. With further visual assessment by oncologists and dermatoscopic image analysis, the overall predictive accuracy can increase to 75%–84%. This project aims to develop an automated classification system using image processing techniques to classify skin cancer based on skin lesion images.

## Problem Statement
To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

## Dataset
The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.
The data set contains the following diseases:
- Actinic keratosis
- Basal cell carcinoma
- Dermatofibroma
- Melanoma
- Nevus
- Pigmented benign keratosis
- Seborrheic keratosis
- Squamous cell carcinoma
- Vascular lesion
  
![image](https://github.com/user-attachments/assets/18f33c59-e724-4ffd-96f6-384832110bb7)

## CNN Architecture

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Melanoma and Pigmented Benign Keratosis have significantly higher numbers of images compared to other categories. This suggests a larger dataset or focus on these particular skin lesion types.
- Basal Cell Carcinoma and Nevus show a moderate number of images, indicating a reasonable amount of data available for these categories.
- Actinic Keratosis, Dermatofibroma, Seborrheic Keratosis, Squamous Cell Carcinoma, and Vascular Lesion have comparatively fewer images. This could imply less data availability or potentially lower prevalence in the studied dataset.
- Applied CNN with multiple entries of hyperparameter by adding/removing dropout, batch normalization, rescaling, augmenting and call back.
- Final model has train_accuracy: 0.8227 - loss: 0.4670 & val_accuracy: 0.8077 - val_loss: 0.5631
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Technologies Used
- Google Collab 1.2.0
- tensorflow 2.18.0
- keras 3.8.0
- pandas 2.2.2
- matplotlib 3.10.0
- Augmentor-0.2.12
- numpy - 1.26.4

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## References
- Efficient way to build CNN architecture from https://towardsdatascience.com/a-guide-to-an-efficient-way-to-build-neural-network-architectures-part-ii-hyper-parameter-42efca01e5d7


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
