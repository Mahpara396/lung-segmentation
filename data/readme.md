Dataset files are not included due to size.
## Dataset
The dataset used in this study is available on Kaggle:
[Lung Cancer Segmentation Dataset](https://www.kaggle.com/datasets/rasoulisaeid/lung-cancer-segment?resource=download)

After downloading, organize it as:

data/
 ├── train/
 │    ├── <subfolder1>/data/
 │    ├── <subfolder1>/masks/
 │    ├── <subfolder2>/data/
 │    └── <subfolder2>/masks/
 └── val/
      ├── <subfolder1>/data/
      ├── <subfolder1>/masks/
      └── <subfolder2>/...
      
Each image and mask is stored as .npy files.
