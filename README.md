# Melanoma_Assignment Nikhil Panchagnula

## General Info

Melanoma is a type od cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis. We are provided a dataset consisting of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). The data set contains the following diseases:

Actinic keratosis
Basal cell carcinoma
Dermatofibroma
Melanoma
Nevus
Pigmented benign keratosis
Seborrheic keratosis
Squamous cell carcinoma
Vascular lesion
Link to my google drive where I kept and used my zip dataset https://drive.google.com/drive/folders/13d9icXqHbgyGDKn2wtYg-XiBhdfnzf2B?usp=drive_link

## Conclusions

Base model performed very well on train but poor in validation, which showed sign of overfitting
To rectify augmentation like rotation, flip and zoom were used along with drop out was used which helped with overfitting, but dropped accuracy of train and validation
Class imbalance was detected and hence augmentation was used to help with it and which provided the best performing model so far
