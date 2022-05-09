# Project-Prep-Series-02-Data-Preparation
Data preparation is a critical prerequisite to any downstream analysis, especially within the context of machine learning appliactions. The purpose of the following workshop is to familiarize students with some data preprocessing basics in Python 3+, using .csv and .png files.

## Part 1: CSV data preprocessing
* Notebook with content + mini assignemnt: `PNG_preprocessing.ipynb`
* Notebook with mini assignment answers: PNG_preprocessing_Mini_Assignment_Answers.ipynb
* THE DATA
All of the csv data that you are provided today comes from the S1200 release of the [Human Connectome Project](http://www.humanconnectomeproject.org/data/) (HCP). This is an open-source initiative containing demographic, behavioural and high-quality neuroimaging data on healthy young adult twin and non-twin siblings.

### 1.1 Behavioral data: `data_csv/unrestricted_HCP_behavioral.csv`

The dataset that you are being provided only contains the open access HCP behavioral features (some are restricted, see [here](https://wiki.humanconnectome.org/display/PublicData/HCP-YA+Data+Dictionary-+Updated+for+the+1200+Subject+Release#HCPYADataDictionaryUpdatedforthe1200SubjectRelease-Instrument:Demographics) for more info). It is possible to apply for permission to access the Tiers 1 and 2 restricted data.

### 1.2 Brain structure volume data: `data_csv/HCP_volumes.csv`

Structural MRI data was acquired from the WU-Minn HCP S1200 Release ([Van Essen et al., 2013](https://pubmed.ncbi.nlm.nih.gov/23684880/); [Glasser et al., 2016](https://pubmed.ncbi.nlm.nih.gov/27571196/)). Volumes were obtained using the high-resolution 3T T1-weighted (T1w) magnetic resonance imaging (MRI) data (n = 1086 subjects, HCP S1200 Reference Manual, downloaded directly from the [HCP online repository](https://db.humanconnectome.org/data/projects/HCP_1200)).

Total brain volume (TBV) as well as the volume and total surface area of 6 other structures (left striatum, right striatum, left thalamus, right thalamus, left globus pallidus, right globus pallidus) were obtained by Nadia Blostein and colleagues from the [Computational Brain Anatomy (CoBrA) Laboratory](https://cobralab.ca/) (Cerebral Imaging. Center, Douglas Mental Health University Institute) under the supervision of Dr. Mallar Chakravarty. Images were processed and volume and surface area measures extracted using a standard lab pipeline that involved the publicly available [minc-bpipe library](https://github.com/CoBrALab/minc-bpipe-library) and [MAGeTbrain segmentation algorithm](https://github.com/CobraLab/MAGeTbrain). More thorough details on image processing and volume obtention can be found [here](https://www.biorxiv.org/content/10.1101/2022.04.11.487874v1).

## Part 2: PNG data preprocessing
* Notebook with content + mini assignemnt: `PNG_preprocessing.ipynb`
* Notebook with mini assignment answers: PNG_preprocessing_Mini_Assignment_Answers.ipynb
* THE DATA
