# Melanoma_Detection_CNN
> Outline a brief description of your project.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- The Classes re-balancing by augmentation method helps a lot the model to generalize well with good accuracy scores train accuracy: 0.9601 - val_accuracy: 0.9057
- Reducing dramatically both under-fitting and over-fitting error problems as first step give more idea to play with hyper-parameter tuning to increase the accuracy for both Train and Validation scores or using transfer learning.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- tensorflow   - version 2.4.1
- pandas       - version 1.3.1
- matplotlib   - version 3.4.2
- numpy        - version 1.19.5
- Augmentor    - version 0.2.10

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->



## Contact
Created by [@https://github.com/yassineelhallaoui] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
