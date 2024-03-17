# Thoracic_Disease_Classification
'\n\nREADME FILE: \n\nThis README file provides an overview of the dataset and methodology used in the project for detecting thoracic diseases in chest X-ray images.\n\nDataset Description:\nThe dataset used in this project is a curated subset derived from the ChestX-ray8 dataset, which originally consisted of 112,120 images from 30,805 unique patients. This subset has been intelligently partitioned into three sets: a training set with around 3,300 images, a validation set containing 1,200 images, and a test set comprising 500 images. The images in the dataset are annotated with text-mined labels for 14 common thoracic pathologies. For the specific needs of this project, a meticulous selection process resulted in a subset comprising approximately 5000 images.\n\nMethodology:\nThe dataset was preprocessed by creating a new column containing the file paths for the chest X-ray images. This was followed by data visualization through bar plots, showcasing the distribution of disease labels concerning patient age and the relationship between disease labels and the number of follow-up examinations. Correlation analysis was also conducted using a heatmap, which revealed no significant correlations among the parameters. A subset of the data was segregated for validation and testing purposes and underwent processing, resizing, and normalization. The training data'
