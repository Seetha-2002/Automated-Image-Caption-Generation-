# Automated-Image-Caption-Generation
## Image Caption Generator using VGG16 and LSTM
This project implements an image captioning system using a Convolutional Neural Network (CNN) and a Long Short-Term Memory (LSTM) network. The VGG16 model is employed to extract image features, while the LSTM network generates captions based on the extracted features. This project utilizes the Flickr 8k dataset as the image-caption dataset.
## Overview
Image captioning involves automatically generating textual descriptions for images. This project combines VGG16 for feature extraction with LSTM to form captions that describe the content of the images.

## Dataset
The Flickr 8k dataset consists of 8,000 images with five captions per image, designed for image captioning tasks. You can download it from Kaggle.

## Model Architecture
Feature Extraction (VGG16): VGG16, a pre-trained model, is used to extract high-level image features from each image.
Sequence Generation (LSTM): An LSTM network takes the extracted image features and generates the corresponding caption.
