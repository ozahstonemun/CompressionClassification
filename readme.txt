# CompressionClassification
This repository contains images JPEG-compressed and classified with a pre-trained Inception-v3 model.
The folders contain both the images and the actual scores output by the classifier for each image (together with those for other images which the classifier seems to recognize as similar, at least to some degree) on every level of compression (Q1-Q100).
The excel file contains the statistics for only the images intended for classification, for quick and easy analysis.

----------------------------------------------------------------
#In addition, we have included classification scores for the original 21 images in .tiff format on new 13 models (other than the Inception-V3). The new inception-v3 among the 13 models is the newer model architecture of the Inception-V3 called "Rethinking the Inception" see: https://keras.io/applications/ for the models provided by keras for easy use.

----------------------------------------------------------------
#Scores and analyses now include those for JPEG2000 and SVD in addition to those for the basic JPEG.