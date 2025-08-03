

# Vegetable Classification

A simple machine learning project for classifying different vegetable classes based on image data. Initially trained on a small dataset, this model can be expanded by adding new vegetable images and retraining to include more classes.

## Overview

This project demonstrates image classification for vegetables using a basic deep learning model. The training and experimentation were done on Google Colab, with datasets stored on Google Drive. Users can configure their own data paths for local or cloud-based training.

## Repository Structure

```
.
├── [model_notebook_file].ipynb   # Jupyter notebook for model development and results
├── [dataset_folder]/             # Image dataset for training/testing
└── README.md                     # Project documentation
```


## Dataset

- **Original dataset location:**
[Google Drive Folder](https://drive.google.com/drive/folders/1XPfvGPstOxuVjnMgO6e_IgYNf8cup3UA?usp=drive_link)
- The dataset contains labeled folders for each vegetable class, storing sample images for classification.

> If you want to use a local dataset instead, make sure to set the correct file path in the project notebook/code.

## Usage

1. **Clone the repository:**

```
git clone https://github.com/AshishhAmin/Vegetable_Classification
cd Vegetable_Classification
```

2. **Prepare your data:**
    - Download the dataset from the provided Google Drive link and upload to your preferred storage (Google Drive or local disk).
    - Organize images in subfolders according to classes (e.g., `./dataset/potato/`, `./dataset/tomato/`, etc.)
3. **Open and run the notebook:**
    - Open the project notebook in Google Colab or JupyterLab.
    - Set the dataset path in the notebook as required.
    - Execute the cells for data preprocessing, model training, and evaluation.
4. **Extend the project:**
    - Add new vegetable images to respective class folders and retrain the model for broader classification.

## Requirements

- Python 3.x
- TensorFlow or PyTorch (as used in the notebook)
- pandas, numpy, matplotlib (for data handling and visualization)
- Google Colab or Jupyter Notebook environment


## Features

- Image-based classification of vegetables
- Easy dataset expansion for new classes
- Training on Colab, with support for cloud or local data storage


## Notes

- The initial version is trained on a small dataset and may be improved with more data and model tuning.
- Dataset folders and code can be easily adapted for similar classification tasks.


## License

For educational, demonstration, and research purposes.

**If you contribute new vegetable images or model improvements, please submit a pull request.**



