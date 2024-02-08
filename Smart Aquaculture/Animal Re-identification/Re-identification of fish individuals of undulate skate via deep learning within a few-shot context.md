# [Re-identification of fish individuals of undulate skate via deep learning within a few-shot context](https://www.sciencedirect.com/science/article/pii/S1574954123000651)

Journal: Ecological Informatics (Q1) 2023

## Abstract
This paper proposes a few-shot Siamese Neural Network to identify undulate skate individuls from photos. 

## Pipeline
Transfer Learning (due to little data)(a pre-trained CNN) -> Data Augmentation -> Siamese Neural Network -> Emsemble Evaluation

## Data
* Most of the images were captured using a reflex camera (objective 15-55 mm) and an action camera GoPro Hero 7 (extracting frames from 4K videos)
* Not sensitive to superficial features (e.g., shadows)  and use visual apperance instead
* 1,138 images(1 - 31, everage 7 images for each individual) of 108 individuals (After preprocessing, 1219 images for 108 individuals)
* Test set: 370 images (4 recaptured individuals)