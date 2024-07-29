# face_mask_detection_YOLO7_CNN
# Project Describtion
The end goal of this project is to detect that if people are wearing maks or not, so in order to achieve  this i used two differend approches :

1- The first approch was using the classic cnn models, but to do this i had to crop images so that every image contain one face and move these pics to the appropriate folders then i builded a cnn model, trained and tested it on the transformed dataset and got 95.5% on accuracy score.

2- The second approach was preforming a custom training using the YOLO 7 model which required transforming the labels of the images from PASCAL VOC into YOLO format and achieved F1 score of 92%.

# About the Dataset

Masks play a crucial role in protecting the health of individuals against respiratory diseases, as is one of the few precautions available for COVID-19 in the absence of immunization. With this dataset, it is possible to create a model to detect people wearing masks, not wearing them, or wearing masks improperly.
This dataset contains 853 images belonging to the 3 classes, as well as their bounding boxes in the PASCAL VOC format.
The classes are:

* With mask
* Without mask
* Mask worn incorrectly

