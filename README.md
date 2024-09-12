# Malware Classification using Deep Convolutional Neural Networks 

## Overview

The proposed work is used for classification of malware images obtained from Malevis dataset : A Dataset for Vision Based Malware Recognition(https://web.cs.hacettepe.edu.tr/~selman/malevis/)
Malevis dataset involves totally 9100 training and 5126 validation RGB images. All the training classes involve 350 image samples while validation set have various number of images.
The RGB images are converted into grayscale images to reduce better computational complexity of image processing as it involves only a single channel instead of three. 


## Model Architecture

![Image alt text](images/Malvision-architecture.JPG)

## Data Visualization

![Image alt text](images/Malvision-images.JPG)
The performance of the model is : Training accuracy - 98.9% , Validation accuracy - 87 %

### The model has been tested on real-time backdoor executables prepared using meterpreter reverse-shell-http payload which is represented in the form of a byte image

