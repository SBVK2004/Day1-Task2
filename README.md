# Day1-Task2
# State Recognition of a given object

## Process involved to successful completion of the project
#### 1. ***Image Preprocessing:***
  ### Applies resizing, normalization, and augmentations (like flipping, rotation) to make the model more robust.
#### 2. ***Train/Validation Split:***
  ### Randomly splits data into 80% for training and 20% for validation.
#### 2. ***Pretrained Model:***
 ### Loads MobileNetV3 (lightweight CNN model pre-trained on ImageNet), and adjusts the final layer for binary classification.
#### 2. ***Training Loop:***  
 ### rains the model over multiple epochs, evaluates on validation set each time, and saves the best-performing model.
#### 2. ***Prediction:***
 ### predicts the new given image as on or off.
