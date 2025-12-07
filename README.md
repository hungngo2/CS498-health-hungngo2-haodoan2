Authors: Hung Ngo (hungngo2@illinois.edu), Hao Doan (haodoan2@illinois.edu)

# Overview
This repository contains the source code for a class project reproducing the CheXpert++ paper.

Key features include:
- Reproducing Chexpert++ model using BERT to do text classification 
- Different ablation and extension study with different BERT models, different sizes of training data and teacher distillation. The code also have some attention visualizations 

# Dependencies
- This notebook is ran on Google Colab, and the first few blocks should install all Python dependencies needed to run, so it should not need to install anything extra
- Some dependencies that are installed include: Pytorch, Numpy and Pandas. 
- Most critically, it need to install Chexpert Labeler (https://github.com/stanfordmlgroup/chexpert-labeler) to perform the manual label rules to produce the dataset for training.

# Instructions to run
- The code is really self contained to run in Google Colab. You will need to download MIMIC-CXR dataset from Physionet: https://physionet.org/content/mimic-cxr/2.1.0/ and save it on Google Colab with this path `/content/mimic-cxr-reports.zip`. After that, the Google Colab should automatically unzip the data and extract the training dataset.


