# Project Name - Melanoma Detection Assignment
> **Problem statement:** To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early.
> It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.



## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Data Reading - Mounted google drive with google colab
- Dataset Creation - Generated Train and Test folder with a batch size of 32 and 180*180 pixels
- Dataset visualisation
- Model Building & training - Created CNN model with 9 O/P classes. Used Rescaling, Convolution Layers, MaxPooling, Dropout, Flatten, Fully Connected Dense Layers
- Used Data Augmentation Technics for Over-fitting
- Checked the distribution of data for class imbalance
- Fixed imbalance problem using Augmentor

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Final model came with more than 80% Training Accuracy and more than 76% of validation accuracy
- BatchNormalization was not a big help and dropped in the final model
- Training Loss and Validation loss are converging towards 0 which is good indication for the model
- There is very low difference between Training Loss and Validation loss thus the Final model generalized it well

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Used Tensorflow
- User Keras Libraries 
- Used numpy
- Used pandas

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by UpGrad Assignment


## Contact
Created by [@AKS-GithubAIML] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->