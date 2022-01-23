# LIGHTHOUSE
This is the repository for the results presented in our manuscript. Please see the <a href='https://github.com/Shimizu-group/LIGHTHOUSE/blob/main/DEMO.ipynb'>DEMO.ipynb</a> file.

Dependencies:
Python anaconda environment, PyTorch, RDKit, subword-nmt

## Install commands
### Virtual environment
conda create -n LIGHTHOUSE_demo<br>
conda activate LIGHTHOUSE_demo
### Install dependencies
conda install pytorch==1.9.0 -c pytorch<br>
conda install matplotlib<br>
conda install scikit-learn<br>
conda install -c conda-forge jupyterlab

conda install -c rdkit rdkit=2021.03.4
### Clone this repository

## Basic Usage
### Initialization
LIGHTHOUSE.setups()
### Predict confidence score
LIGHTHOUSE.predict_confidence (chemical, protein)
### Predict interaction score
LIGHTHOUSE.predict_interaction (chemical, protein)
