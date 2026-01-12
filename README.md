# ODS Jamboree AI Readiness Project

This repository contains three example python scripts (.ipynb files) developed during the NCI ODS Data Jamboree. The scripts are specific to the data types used in our project (imaging and clinical) and can be used as a example for others who are looking to assess the AI-readiness of datasets. 

## Environment

All scripts were developed on the Seven Bridges - Cancer Genomics Cloud (SB-CGC) platform using the JupyterLab environment with the SB Data Science environment (Python 3.11).

All referenced file paths and data direct to the SB-CGC folder structure (i.e., all data files were in the /sbgenomics/project-files/ folder, all output files wrote to the /sbgenomics/output-files/ folder, etc.).

The following libraries need to be pre-installed to run portions of the scripts:
- os	
- pandas
- numpy
- random
- pydicom
- collections
- math

## Brief Description of the Files

A brief description of the purpose of each script can be found below. Additional information and comments can be referenced in the scripts. 
1. *1_Jamboree_Extract Samples.ipynb* -- cleans the Excel file from C3DC Hub and extracts samples from the MCI and RMS studies reference files from both CCDI Hub and C3DC
2. *2_Extract_DICOM_Metadata.ipynb* -- extracts metadata from all DICOM files in the sample and assesses the 3 data quality measures: consistency, completeness, and outliers
3. *3_Clinical_Data_Analysis.ipynb* -- explores the general characteristics of the clinical data files (participant/case and sample/biospecimen) and assesses the 3 data quality measures: consistency, completeness, and outliers
