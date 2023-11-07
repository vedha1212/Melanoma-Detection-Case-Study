# Melanoma Detection Case Study



## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis. The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

The data set contains the following diseases:

1. Actinic keratosis
2. Basal cell carcinoma
3. Dermatofibroma
4. Melanoma
5. Nevus
6. Pigmented benign keratosis
7. Seborrheic keratosis
8. Vascular lesion
9. Squamous cell carcinoma


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Conclusion 1 from the analysis : The model was overfitting in the beginning and validation accuracy was very low.
- Conclusion 2 from the analysis : Data Imbalance was identified in the data and Augmentor model has been used to remediate this.
- Conclusion 3 from the analysis : After fixing the data imbalance using Augmentor library, overfitting of the data has been reduced. We achieved a low bias and low variance model with training accuracy - 93% and validation accuracy of 89%.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python
- TensorFlow
- Keras
- Matplotlib
- Seaborn

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements

This project was inspired by Upgrad team and the CNN topics taught.


## Contact
Created by Vedha Nanjappa[@vedha1212] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
