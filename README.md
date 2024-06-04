# Prerequisites
Please make sure you have CUDA installed on your device

# Dataset
See https://tbrain.trendmicro.com.tw/Competitions/Details/35

# Directory Structure (Notice the directory names)
```
unet.ipynb
/train_dataset
├── img
│   ├── TRA_RI_2000000.jpg
│   │   ...
│   ├── TRA_RO_2004319.jpg
└── mask_img
    ├── TRA_RI_2000000.png
    ├── ...
    └── TRA_RO_2004319.png
/test_dataset
├── PRI_RI_2000000.jpg
├── ...
└── PUB_RO_2000719.jpg
```  

# Data Preparation
* Download the dataset from the link provided above
* Make sure that files are arranged as mentioned above (public and private set are merged into one)

# Model Training and Testing
* See unet.ipynb
