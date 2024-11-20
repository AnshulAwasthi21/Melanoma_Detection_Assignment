# Melanoma Detection Assignment
> This project is a multiclass classification implementation of CNN model on Skin cancer dataset. 


## Table of Contents
* [General Info](#general-information)
* [Steps Involved](#steps-involved)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
-    Built a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

-    The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

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

## Steps Involved

- Data Loading
- Baseline Model Building
- Training the Model and testing the model
- Building an augmented model
- Training the augmented model and testing the model
- Countering Class Imbalance with augmentor
- Building the final model
- Training the final model and testing the model

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
As the accuracy of the model increases, the loss decreases. The final model has an accuracy of ~75% and a loss of 0.3. The model is able to predict the classes with a high accuracy.
Furthermore, Augmenting the data and countering class imbalance helped in improving the accuracy of the model.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used

- Python
- Tensorflow
- Keras
- Augmentor
- Matplotlib
- NumPy

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This project was created as part of a multiclass classification model using a custom convolutional neural network in TensorFlow for IIITb and UpGrad.


## Contact
Created by [@AnshulAwasthi21] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->