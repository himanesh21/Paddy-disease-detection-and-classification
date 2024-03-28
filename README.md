# Paddy-disease-detection-and-classification
this repository contains source code related to paddy disease classification developed by using pytorch deep learning library.
# dataset
The data used for this project is collected from Kaggle named paddy disease classification. The dataset has ten classes and consists of 10,406 images.
Images have the following characteristics: The image has a height of 640 pixels and a width of 480 pixels, with a maximum pixel value of 255.0, the minimum pixel is 0.0, the mean pixel value is 115.9670, and the standard deviation is 71.6155.

dataset link :https://drive.google.com/drive/folders/1wYOcrSzxh8MEXws0f_R0FpCf1kOgmM02?usp=sharing
# model
Mobilenetv2 is a pre-trained deep transfer learning model created by Google and designed for mobile and resource-constrained environments. Mobilenetv2 is built upon the Mobilenetv1 architecture
# transformation
1.resized all of the images into 224x224.
2.normalized using imagenet mean and std values.
