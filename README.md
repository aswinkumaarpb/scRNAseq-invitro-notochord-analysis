# scRNAseq-invitro-notochord-analysis
Single Cell RNA-Seq Analysis

This repository contains scripts and notebooks to analyse the single cell RNA seq data that is stored in **Blin Datastore\ngs**.
Prerequisites

To use the code in this repository, the easiest way is to download and install Anaconda (https://anaconda.org/) and download from this repository the RNAseq_Conda_Enviroment.yml file (it can also be found in Blin Datastore \Anaconda Environments\RNAseq_Conda_Enviroment.yml).
Installation

Once you have installed Anaconda, open an anaconda prompt and run the following command:

conda env create --name RNAseq --file=RNAseq_Conda_Environment.yml


A Few Things to Take into Account:


The file name can be changed to whatever you name the file you download.
You can change the name of the environment created by changing what comes after --name.
The command conda env create --name RNAseq --file= has to be run from the directory where you have saved the downloaded file or by replacing the filename by the path to the directory where the file is. To change paths in conda use cd.
You will need to activate the environment (conda activate RNAseq) before launching Jupyter Notebook from this environment.

After you run this command, Anaconda might ask for your permission (Y/N) to install the libraries. At the end this should create a new environment with all the required libraries and the required versions.
Activation

Once the environment is created, activate it with the following command:

conda activate RNAseq


Navigate to the directory where you have saved the code and data from this repository:

cd "path to directory"


Running Jupyter Notebook

Once in the correct directory and with the conda environment activated, run:

jupyter notebook


This will open a browser tab with Jupyter Notebook, and you will be able to see the files as they appear on the file explorer. Open the Python script and run it.
