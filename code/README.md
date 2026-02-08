**Instructions for Running Code**

Instructions for running each part of our code are detailed in markdown in our jupyter notebook. To run our code, numerous packages are needed, all of which are listed below. Primarily, we utilize a dataset off of kagglehub. To download the dataset, the KaggleHub API needs to be used. Simply uncomment the last line of the first cell and add in the pathname to KaggleHub's cache on your local computer. Outside of the downloading the dataset, the code can simply be run as is. 

**List of Packages Required:**

Kagglehub

OpenCV

NumPy

SciKit Learn

TQDM

PyTorch

TorchVision

TensorBoard

torchsummary

**Files and Directories:**

To run our code, only the jupyter notebook is needed. The other file and folder will be created during execution of our code. 

finalproject.ipynb: This contains all our code for our final project. Everything you need to run our code is located in this file. 

best.pt: This is simply the file that contained our saved model from the epoch with the highest validation accuracy. This file is crucial for loading in this model during the inference stage. 

runs: This is a folder that contains PyTorch TensorBoard logging. It consists of TensorBoard event files that store training and validation metrics, specifically loss and accuracy, across each epoch. These metrics can be visualized easily using this command line argument: `tensorboard --logdir=runs`.

