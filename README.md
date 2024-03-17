# Thoracic_Disease_Classification
# README FILE:

## Overview

This README file provides an overview of the dataset and methodology used in the project for detecting thoracic diseases in chest X-ray images.

## Dataset Description

The dataset used in this project is a curated subset derived from the ChestX-ray8 dataset, which originally consisted of 112,120 images from 30,805 unique patients. This subset has been intelligently partitioned into three sets:

- Training set: Approximately 3,300 images
- Validation set: 1,200 images
- Test set: 500 images

The images in the dataset are annotated with text-mined labels for 14 common thoracic pathologies. For the specific needs of this project, a meticulous selection process resulted in a subset comprising approximately 5,000 images.

## Methodology

1. **Data Preprocessing**: The dataset was preprocessed by creating a new column containing the file paths for the chest X-ray images.

2. **Data Visualization**: Data visualization was performed through bar plots, showcasing the distribution of disease labels concerning patient age and the relationship between disease labels and the number of follow-up examinations.

3. **Correlation Analysis**: Correlation analysis was conducted using a heatmap, which revealed no significant correlations among the parameters.

4. **Data Segregation**: A subset of the data was segregated for validation and testing purposes.

5. **Data Processing**: The segregated subset underwent processing, resizing, and normalization.

## Note

The training data...
