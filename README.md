# Clustering, imputation, and integration for spatial transcriptomics using spatiotemporal gaussian mixture variational autoencoder

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.8141084.svg)](https://doi.org/10.5281/zenodo.8141084)

![](https://github.com/narutoten520/STGMVA/blob/82e612fd371aaaa0f6b7ce7179c4e441690952ad/STGMVA.jpg)

## Overview
STGMVA is a comprehensive analysis toolkit employs a spatiotemporal gaussian mixture variational autoencoder to tackle these tasks effectively. STGMVA consists of two stages: pretraining the gene expression and spatial location using a gaussian mixture model, and learning the embedding vectors through a variational graph autoencoder. Results demonstrate STGMVA surpasses state-of-the-art approaches on various spatial transcriptomics datasets, exhibiting superior performance across different scales and resolutions. Notably, STGMVA achieves the highest clustering accuracy in human brain, mouse hippocampus, and mouse olfactory bulb tissues. Furthermore, STGMVA enhances and denoises gene expression patterns for gene imputation task. Additionally, STGMVA has the capability to correct batch effects and achieve joint analysis when integrating multiple tissue slices.

## Requirements
You'll need to install the following packages in order to run the codes.
* python>=3.8
* torch>=1.8.0
* cudnn>=10.2
* numpy==1.22.3
* scanpy==1.9.1
* anndata==0.8.0
* rpy2==3.4.1
* pandas==1.4.2
* scipy==1.8.1
* scikit-learn==1.1.1
* tqdm==4.64.0
* matplotlib==3.4.2
* R==4.0.3
* Squidpy
## Tutorial
For the step-by-step tutorial, please refer to:
[https://deepst-tutorials.readthedocs.io/en/latest/](https://deepst-tutorials.readthedocs.io/en/latest/)

## Citation
...
