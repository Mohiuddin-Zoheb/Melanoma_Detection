# Melanoma Detection
> We have build a multiclass classification model using a custom convolutional neural network in TensorFlow. .


Problem statement: To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

The data set contains the following diseases:

Actinic keratosis
Basal cell carcinoma
Dermatofibroma
Melanoma
Nevus
Pigmented benign keratosis
Seborrheic keratosis
Squamous cell carcinoma
Vascular lesion


## Conclusions
- Using various techniques, we have handled several issues to some extent
- We have used BatchNormalization and dropout layers
- we have also usee Augmentor library to handle class imbalnce
- Overall, we have managed to handle overefitting
- but the training and val_accuracy is still low

#### We can imporve the qccuracy of the model by following methods:
- Adding more data
- adding more layers keeping in mind to include BatchNormalization and dropout layers
- Increasing the number of epochs 

