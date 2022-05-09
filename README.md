# Project-Prep-Series-02-Data-Preparation
Data preparation is a critical prerequisite to any data analysis or machine learning application. The purpose of the following workshop is to familiarize students with some data preparation (ie preprocessing) basics in Python 3+, using .csv and .png files.

Part 1 will focus on .csv data preparation and we will be going through the `CSV_preparation.ipynb` notebook. This notebook contains a mini assignment, the answers of which can be found in `CSV_preparation_mini_assignment_answers.ipynb`.

Part 2 will focus on .png (2D image) data preparation and we will be going through the `CSV_preparation.ipynb` notebook. This notebook contains a mini assignment, the answers of which can be found in `CSV_preparation_mini_assignment_answers.ipynb`.

## Part 1: About the CSV Data

### 1.1 Behavioral data: `data_csv/unrestricted_HCP_behavioral.csv`

The dataset that you are being provided only contains the open access HCP behavioral features (some are restricted, see [here](https://wiki.humanconnectome.org/display/PublicData/HCP-YA+Data+Dictionary-+Updated+for+the+1200+Subject+Release#HCPYADataDictionaryUpdatedforthe1200SubjectRelease-Instrument:Demographics) for more info). It is possible to apply for permission to access the Tiers 1 and 2 restricted data.

### 1.2 Brain structure volume data: `data_csv/HCP_volumes.csv`

Structural MRI data was acquired from the WU-Minn HCP S1200 Release ([Van Essen et al., 2013](https://pubmed.ncbi.nlm.nih.gov/23684880/); [Glasser et al., 2016](https://pubmed.ncbi.nlm.nih.gov/27571196/)). Volumes were obtained using the high-resolution 3T T1-weighted (T1w) magnetic resonance imaging (MRI) data (n = 1086 subjects, HCP S1200 Reference Manual, downloaded directly from the [HCP online repository](https://db.humanconnectome.org/data/projects/HCP_1200)).

Total brain volume (TBV) as well as the volume and total surface area of 6 other structures (left striatum, right striatum, left thalamus, right thalamus, left globus pallidus, right globus pallidus) were obtained by Nadia Blostein and colleagues from the [Computational Brain Anatomy (CoBrA) Laboratory](https://cobralab.ca/) (Cerebral Imaging. Center, Douglas Mental Health University Institute) under the supervision of Dr. Mallar Chakravarty. Images were processed and volume and surface area measures extracted using a standard lab pipeline that involved the publicly available [minc-bpipe library](https://github.com/CoBrALab/minc-bpipe-library) and [MAGeTbrain segmentation algorithm](https://github.com/CobraLab/MAGeTbrain). More thorough details on image processing and volume obtention can be found [here](https://www.biorxiv.org/content/10.1101/2022.04.11.487874v1).

## Part 2: About the PNG Data

We will be using 20 2D chest X-ray images (.png files) from the 500 images available in the open-access [Pulmonary Chest X-Ray Abnormalities](https://www.kaggle.com/kmader/pulmonary-chest-xray-abnormalities) Kaggle dataset. This data was collected by the National Library of Medicine (USA) in collaboration with Shenzhen No.3 People’s Hospital, Guangdong Medical College (China). More info can be found in `data_png/NLM-ChinaCXRSet-ReadMe.docx`. `chest_xrays_pngs` contains the 20 .png files, 10 of which represent a normal lung (`CHNCXR_ID_0.png`) and 10 of which represent an abnormal lung (`CHNCXR_ID_1.png`).

