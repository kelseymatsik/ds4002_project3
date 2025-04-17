# Project 3: Tumor Detection 
By: Emma Mills and Kelsey Matsik - Group 22 


## Contents of the Repository 
This repository contains all the work for Project 3 of DS 4002: Prototyping, which has the goal of working with image data. The goal of this project and the content of this repository is to answer the question:

Are glioma tumors harder to correctly classify than meningioma and pituitary tumors (generally slower-growing) given their rapid growth and invasive nature? 

## 1. Software and Platform 
Throughout this project, we used GitHub, Google Colab, and Python. The packages we used were h5py, numpy, os, cv2, glob, tqdm, warnings, sklearn.model, tensorflow, tensorflow.keras, tensorflow.keras.metrics, and matplotlib. All of these packages would have to be downloaded in order to run the notebooks. Both Windows and Mac were used to complete this project.

## 2. Directory 

```
ds4002_project3/
├── DATA/
│   └── Obtaining the Data.md
├── OUTPUT/
│   ├── Frequency of Tumor Types.png
│   ├── Glioma.png
│   ├── Meningioma.png
│   └── Pituitary.png
├── SCRIPTS/
│   ├── .ipynb_checkpoints/
│   │   └── 2_analysis_rc-checkpoint.ipynb
│   ├── 1_preprocessing_EDA.ipynb
│   └── 2_analysis_rc.ipynb
├── LICENSE.md
└── README.md
```

## 3. Reproducing the Results
1. [Clone the repository] (https://github.com/kelseymatsik/ds4002_project3.git)
2. Follow the instructions for obtaining the data outlined in DATA/Obtaining the Data.md
3. Perform preprocessing by running each code in SCRIPTS/1_preprocessing_EDA.ipnyb in order. Be sure to replace file paths with the appropriate ones for your user
4. Run CNN analysis via SCRIPTS/2_analysis_rc.ipynb. For best results, use a machine with a dedicated GPU and sufficient memory to accelerate model training and inference.

## References  
[1] J. Cheng, “Brain Tumor Dataset,” figshare, 2017. [Online]. Available: <https://figshare.com/articles/dataset/brain_tumor_dataset/1512427>
