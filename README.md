# Skin_Cancer_detection_CNN


> The main purpose of this project is to build a CNN based model which can accurately detect melanoma. 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths.
- A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

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
- With initial CNN model build based on available images, model become overfit to give high training accuracy of 90% while validation accuracy remains 54%
- Data Augmentation resolves this issue to the extent to give both training and validation accuracy to 60%, but remains more scope to improve accuracy
- Class rebalancing improves accuracy by major extent by adding more images to the class where sample number is very less. The final validation accuracy remains at 83% after 50 epochs
- 




## Technologies Used
- CNN mdodel


## Acknowledgements
Give credit here.
- This project was inspired by UPGRAD and helped by Upgrad Faculty Aniket Chabra and Sayam Dey



## Contact
Created by [@RahulAlkari] - feel free to contact me!
