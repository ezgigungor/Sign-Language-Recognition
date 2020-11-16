# Sign Language Prediction with Two-Stream CNNs 

Video action recognition with two-stream CNN's using MS-ASL dataset.

## Overview

The model consists of two CNNs, one using a single RGB frame and another one using grayscale optical flow images generated from the video.
These models are fused before the last fully-connected layer.
