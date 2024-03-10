# EyeForBlind
This GitHub repository contains the implementation of a deep learning model capable of generating captions for images in the form of speech. 
The model is designed to aid blind individuals in understanding the contents of images by converting them into spoken descriptions. The caption generation is facilitated by a combination of Convolutional Neural Networks (CNN) and Recurrent Neural Networks (RNN), with an attention mechanism, trained on the Flickr8K dataset.

This GitHub repository contains the implementation of a deep learning model capable of generating captions for images in the form of speech. The model is designed to aid blind individuals in understanding the contents of images by converting them into spoken descriptions. The caption generation is facilitated by a combination of Convolutional Neural Networks (CNN) and Recurrent Neural Networks (RNN), with an attention mechanism, trained on the Flickr8K dataset.

## Problem Statement
The primary objective of this project is to develop a model that can describe the contents of an image through speech. By leveraging deep learning techniques, particularly CNNs for feature extraction and RNNs for sequence generation, the model aims to provide accurate and descriptive captions for images. This use-case is particularly beneficial for visually impaired individuals, enabling them to gain a better understanding of visual content through audio descriptions.

## Features
- Utilizes a CNN-based encoder to extract features from images.
- Implements an RNN-based decoder with attention mechanism for generating captions.
- Extended application of the "Show, Attend and Tell: Neural Image Caption Generation with Visual Attention" paper.
- Employs a text-to-speech library to convert generated captions into speech.

## Dataset
The dataset utilized for training and evaluation is sourced from the Kaggle website. It comprises sentence-based descriptions for 8,000 images, each paired with five different captions. These captions aim to provide clear and concise descriptions of the salient entities and events depicted in the corresponding images.


