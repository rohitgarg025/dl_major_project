# Supervised, Self Supervised and Semi-supervised Deep Learning Approaches for Image Classification

## Overview

This repository contains Major Project submission, titled: __Supervised, Self Supervised and Semi-supervised Deep Learning Approaches for Image Classification__, for partial fulfillment of Deep Learning course[CS F425] at BITS Pilani Goa Campus. In this work, we :

* Explored 3 deep learning approaches for classification:
    * supervised deep learning approach
    * constrastive self-supervised learning using Barlow Twins loss
    * semi-supervised deep learning approach using pseudo labelling technique.
* Compared the performances of three convolutional neural network models: ConvNet, ResNet18 and our own WideResNet(WRN-45-2) through three learning approaches.
* Used STL-10 dataset exclusively.[Link](https://cs.stanford.edu/~acoates/stl10/) 
* Constructed t-SNE visualizations for study of embeddings.
* Performed ablation study of varying ratios of labelled and unlabelled data on all three models.
* Produced an increment in accuracy of prediction of WRN-45-2 from 72 %(supervised) to 75 %(semi-supervised).
* Inferred that semi-supervised approach produces better performance than both of individual supervised and self-supervised approach.
