# FireFront-Detect
Codes Used on My Thesis Work - Supervised Methods on Fire and Smoke detection ( FireFront Project )
All the codes produced are ment to be executed on Google Colab environment using Python3


On first part of the project I worked on a global image classifier using different networks. The objective was to detect if a certain image contains fire or not, not giving any information about the localization of that fire.
Networks used:

AlexNet: [Contribution guidelines for this project](main/Global Image Classifier/AlexNet/AlexNet Fire detection.ipynb)

SqueezeNet: [Global Image Classifiers](SqueezeNet.pythn)

Then I moved on to segmentation networks in which I used fully supervised training methods to train. The networks are able to segment the 
given images in areas of fire and non-fire ( binarization )

