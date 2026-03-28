# Fake-News-Detection-System-With-Explainable-AI
Data Science Master's Thesis.
This project is for the Master's Thesis conducted by Sheikh Khairul Momin Mohammad Tahmid (k2502054), a student of Kingston University during the year 2025 (uploaded in January 2026).

## Project Setup and File Structure

Due to GitHub file size limitations, the dataset and executed model files are provided as compressed ZIP archives. To correctly set up the project environment, please follow the steps below:

1. Download all ZIP files provided in this repository.
2. Extract each ZIP file into the same root directory as this repository.
3. After extraction, the project directory should contain the following folders alongside the source code:
Dataset/
Executed Model/
Output/

## Execution Environment and Data Handling

This project was developed and executed primarily using Google Colab, and the complete model training and evaluation pipeline was run within the Colab environment. All experiments leverage the computational resources provided by Google Colab for model training and inference. The dataset used for training and testing is loaded directly from Google Drive, and all intermediate and final outputs generated during model training are saved back to Google Drive under the Executed Model directory. As a result, file paths related to dataset loading and output storage are explicitly configured for Google Drive access and must be updated by the tester according to their own Drive structure.

The explainable AI component of this study is also executed in Google Colab, but utilises local machine resources for model interpretation and visualisation. For this purpose, the trained model outputs stored in Google Drive (under Executed Model) must be downloaded locally before running the explainability scripts.

Consequently, users reproducing this work are required to:

1. Update the file paths used to load the dataset from Google Drive
2. Update the file path used to save the trained model under the Executed Model directory in Google Drive
3. Update the file paths used to read the downloaded Executed Model directory,
4. Update the output paths where generated results and visualisations are saved.

These steps are necessary to ensure correct execution and full reproducibility of the experimental results presented in the thesis

No further configuration is required. All scripts and notebooks assume this directory structure when loading data and models. This setup ensures full reproducibility of the experiments and results presented in this thesis.

