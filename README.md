# Surface-crack


## Overview
This project focuses on building a Convolutional Neural Network (CNN) to classify images of concrete surfaces as either with cracks (positive) or without cracks (negative). The dataset includes 40,000 images (20,000 per class), each of size 227x227 pixels with RGB channels, derived from 458 high-resolution images (4032x3024 pixels) as described in Zhang et al. (2016). The primary objective is to accurately detect surface cracks while analyzing and optimizing the performance of the model.

### Tasks
**1.  Preprocessing**

*  Perform channel normalization to standardize the image data for improved network performance.
  
**2.  Model Construction and Training**

*  Build a CNN architecture optimized for detecting surface cracks.
*  Train the network using the preprocessed dataset.
  
**3.  Performance Evaluation**

*  Calculate performance metrics (e.g., accuracy, precision, recall, F1-score).
*  Analyze the results to evaluate model effectiveness.

**4.  Bonus Task**

*  Apply data augmentation techniques (e.g., rotation, flipping, tilting) to improve the generalization and robustness of the model.
