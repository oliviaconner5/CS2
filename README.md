# CS2

## Table of Contents
- SRC:
  - This folder contains all of the source code for our project. This folder contains all code used to load and combine the image data as well as structure the final model for training.
- DATA:
  - This folder is where we store all datasets being used for this project. Specifically it has three subfolders that contain all image data for the respective kind of tumor that the image displays (benign, malignant, or normal). Within each of these folders, the images are further divided into two folders titled "full" or "masked" based on the image type.
- Figures:
  -  This folder contains exploratory plots looking into the distribution of data between the three types of tumors. It also contains a confusion matrix displaying the results of our model.

## SRC
### Installing/ Building our code
- It is recommended to run the notebook files in an IDE that supports both Jupyter Notebooks and R markdown files such as Pycharm.
- These files use the 'tidyverse' and 'dplyr' R libraries and the json, re, pickle, numpy, pandas and sklearn Python libraries
- File paths may be incorrect on your machine, you are recommended to check all file paths before running.


### Notebook Files
| Notebook Name | Decription |
| -------- | -------- |
| transfer_learning.ipynb | This notebook contains all code used for the completion of the project. This includes data cleaning, creating the dataset, transfer learning with MobileNetV2, and fine tuning the model. |
| P2-Visualizations.rmd | This notebook cleans code for creating visualizations to view the general distribution of the data |
