# A Semi-Supervised Multi-Stage Pipeline for Lung Tumor Segmentation

## Description
This repository contains the implementation of a semi-supervised multi-stage framework for lung tumor segmentation using contrastive learning (SimCLR) and adaptive K-means clustering.

The experiments were implemented in Google Colab.

## Dataset
Dataset is available on Kaggle:
https://www.kaggle.com/

After downloading, organize as:

data/
 ├── train/
 │    ├── data/
 │    └── masks/
 └── val/
      ├── data/
      └── masks/

Each image and mask is stored as .npy file.

## Installation
pip install -r requirements.txt

## Usage
Open main.ipynb and run all cells.

## Output
Trained encoder saved in outputs folder.

## Reproducibility
Random seed fixed to 42.

## License
MIT
