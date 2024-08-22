# UvA Information Retrieval 0
Assignments for the Zoekmachines (IR0) course at the University of Amsterdam.

## Setup
Follow the steps below to set up the environment for the assignments.

1. Clone this repository to your local machine:
```bash
git clone git@github.com:irlabamsterdam/uva-ir0-assignments.git
```
2. Enter the repository:
```bash
cd uva-ir0-assignments
```
3. We use Python 3.10 for the assignments. All additional dependencies are listed in `environment.yaml`. To set up a virtual environment with the correct Python version and dependencies, use [conda](https://docs.anaconda.com/miniconda/) or [mamba](https://mamba.readthedocs.io/en/latest/installation/mamba-installation.html). Mamba is a faster alternative to conda, and you can replace `conda` with `mamba` in all commands below:
```bash
conda env create -f environment.yaml
``` 
4. Activate the environment in your current terminal session:
```bash
conda activate uva-ir0-assignments
```
5. Launch a JupyterLab server to work on the assignments:
```bash
python -m jupyterlab
```
