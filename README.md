# Classifying Benign and Malignant Breast Cancer Histopathology Images

This project aims to optimize a CNN to accurately classifiy breast cancer histopathology images. To have a baseline to compare against, a linear SVM classifier with SGD is first trained and evaluated. The CNN optimized is the ResNet-34 model from PyTorch. Optimization included selecting layers to unfreeze, tuning hyperparameters such as learning rate and number of epochs, along with data augmentation. Both the SVM and CNN were evaluated using identical metrics. This project demonstrates the full pipeline from data preparation to model evaluation, highlighting both machine learning development and applied computational analysis in biomedical imaging.

## Contents

This folder includes:

- **Paper**: Full write-up describing our methodology, experiments, and results.  
- **Code**: Scripts to reproduce the experiments and results. More detailed information for running the program is described inside the code folder. 

## Contributions 

This project was completed in collaboration with Lalith Suresh '26 (Swarthmore College).

My contributions:
- Designed and modified the CNN architecture to improve performance.
- Optimized hyperparameters and conducted training, validation, and testing.
- Implemented initial data preprocessing to prepare the dataset for model training.
