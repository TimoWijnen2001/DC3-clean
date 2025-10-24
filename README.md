Python 3.12.10 was used for this project.

You should have final.ipynb, the 2 zip-files with masks_labels and bleaching_data from reefsupport, and an empty data folder.

First you unzip the two zip-files into the data folder. Since we're downloading from Google Drive, the data may come in many folders. 
This may require some manual folder restructuring which includes extracting folder from nested folders. Nothing has to be done to the 
but in the end, the directory should look as follows:


NOTE: THIS NEEDS TO BE CHANGED SINCE WE DONT USE THE BENTHIC DATASET FROM CORALSEG
├── data
│   ├── benthic_datasets
│   │   └── reef_support
│   │       ├── SEAFLOWER_BOLIVAR
│   │       │   ├── images
│   │       │   ├── masks
│   │       │   └── masks_stitched
│   │       ├── SEAFLOWER_COURTOWN
│   │       │   ├── images
│   │       │   ├── masks
│   │       │   └── masks_stitched
│   │       ├── SEAVIEW_ATL
│   │       │   ├── images
│   │       │   ├── masks
│   │       │   └── masks_stitched
│   │       ├── SEAVIEW_IDN_PHL
│   │       │   ├── images
│   │       │   ├── masks
│   │       │   └── masks_stitched
│   │       ├── SEAVIEW_PAC_AUS
│   │       │   ├── images
│   │       │   ├── masks
│   │       │   └── masks_stitched
│   │       ├── SEAVIEW_PAC_USA
│   │       │   ├── images
│   │       │   ├── masks
│   │       │   └── masks_stitched
│   │       ├── TETES_PROVIDENCIA
│   │       │   ├── images
│   │       │   ├── masks
│   │       │   └── masks_stitched
│   │       └── UNAL_BLEACHING_TAYRONA
│   │           ├── images
│   │           ├── masks
│   │           └── masks_stitched
│   └── coral_bleaching
│       ├── images
│       ├── masks_bleached
│       └── masks_non_bleached
├── final.ipynb
├── mask_labels.tar.gz
├── README.md
├── reef_support.tar.gz
└── 