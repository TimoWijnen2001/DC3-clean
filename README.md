# Coral Bleaching Analysis and Segmentation

This project focuses on analyzing coral bleaching using deep learning–based image segmentation and visual scoring.  
It includes preprocessing, model training, and generation of various visual and quantitative evaluation outputs.

---

## Environment Setup

- Python version: 3.12.10  
- All dependencies are listed in `requirements.txt`.
- Install CUDA for faster model training.

---

## Required Files and Directory Setup

You should have:
- `main.ipynb`
- `coral_dataset.py`
- `requirements.txt`
- Two zip files: **masks_labels** and **bleaching_data** (from ReefSupport)
- An empty `data/` folder

If something is wrong with the zip files, they can be downloaded from the drive. The folders are under "01_data/benthic_datasets/mask_labels" and "01_data/coral_bleaching/reef_support".

Unzip both archives into the `data/` directory.  
When downloading from Google Drive, the files may be nested within several folders — extract and reorganize them as shown below:


├── data  
│   ├── benthic_datasets  
│   │   ├── SEAFLOWER_BOLIVAR  
│   │   │   ├── images  
│   │   │   ├── masks  
│   │   │   └── masks_stitched  
│   │   ├── SEAFLOWER_COURTOWN  
│   │   │   ├── images  
│   │   │   ├── masks  
│   │   │   └── masks_stitched  
│   │   ├── SEAVIEW_ATL  
│   │   │   ├── images  
│   │   │   ├── masks  
│   │   │   └── masks_stitched  
│   │   ├── SEAVIEW_IDN_PHL  
│   │   │   ├── images  
│   │   │   ├── masks  
│   │   │   └── masks_stitched  
│   │   ├── SEAVIEW_PAC_AUS  
│   │   │   ├── images  
│   │   │   ├── masks  
│   │   │   └── masks_stitched  
│   │   ├── SEAVIEW_PAC_USA  
│   │   │   ├── images  
│   │   │   ├── masks  
│   │   │   └── masks_stitched  
│   │   ├── TETES_PROVIDENCIA  
│   │   │   ├── images  
│   │   │   ├── masks  
│   │   │   └── masks_stitched  
│   │   └── UNAL_BLEACHING_TAYRONA  
│   │       ├── images  
│   │       ├── masks  
│   │       └── masks_stitched  
│   └── coral_bleaching  
│       ├── images  
│       ├── masks_bleached  
│       └── masks_non_bleached  
├── coral_dataset.py  
├── main.ipynb  
├── mask_labels.tar.gz  
├── README.md  
├── reef_support.tar.gz  
└── requirements.txt  


Once the directory matches the structure above, open and run main.ipynb.
Executing the notebook from top to bottom will reproduce all visualizations and results.

---

## Notebook Outline

| Section | Description |
|----------|--------------|
| **0** | Imports and setup |
| **1** | Data preprocessing and cleaning |
| **2** | Model training and evaluation |
| **3** | Computation of visual bleaching scores |
| **4** | Derivation of severity score |
| **5** | Extra visualizations and summary outputs |


All generated images and figures are saved in the visualisations/ directory.
