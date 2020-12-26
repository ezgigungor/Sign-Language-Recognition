# Sign Language Prediction with Two-Stream CNNs 

Video action recognition with two-stream CNN's using [MS-ASL dataset](https://www.microsoft.com/en-us/research/project/ms-asl/).

## Overview

The model consists of two CNNs, one using a single RGB frame and another one using stacked grayscale optical flow images generated from the video.
These models are fused before the last fully-connected layer. (Early-fusion)

## Data

Detailed description of the dataset can be found in [the official paper](http://export.arxiv.org/pdf/1812.01053).

## Hyper-Parameters
- Learning rate: 0.001
- Number of epochs: 32
- Batch size: 64
- Loss function: Cross entropy loss
- Optimizer: Adam


## Network Architecture

Two-stream CNN architecture is the one proposed in the [paper](	arXiv:1406.2199) by  Karen Simonyan and Andrew Zisserman. Only difference is the usage of early fusion instead of late fusion.

