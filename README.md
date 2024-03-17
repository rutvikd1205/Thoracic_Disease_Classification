# X-Ray Image Analysis

This repository contains code for analyzing X-ray images to predict the presence of diseases using machine learning models.

## Setup

To get started, first install the required Python libraries:

```bash
pip install opacus
pip install diffprivlib
pip install --upgrade tensorflow-privacy

#Models
##Model 1: Binary Classification Neural Network
This model predicts the presence of diseases using follow-up, age, gender, and other factors.

##Model 2: Convolutional Neural Network (CNN)
This CNN model uses X-ray images to predict diseases.

##Model 3: VGG16 with Additional Layers
A modified VGG16 model with additional layers for improved performance.

##Model 4: Differential Privacy Model
A model trained with differential privacy for privacy-preserving predictions.

Evaluation
Model Performance
Model 1: Accuracy - 57.2%
Model 2: Accuracy - 64.8%
Model 3: Accuracy - 55.4%
Confusion Matrix



Conclusion
These models provide insights into the diagnosis of diseases from X-ray images, with Model 2 showing the best performance.


