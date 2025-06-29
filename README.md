# ml-supervised-classification-20newsgroups

# Project Overview
### Classifying Email Texts into Topics Using ML Models

This Project builds a text classification model.  
The model predicts the category of a text based on the email body.  
Since we have correct labels, this is a supervised learning task.  
In this notebook, I use the fetch_20newsgroups function to load sample data, which is part of sklearn.datasets.


## Notebook
https://github.com/refuel-code-135/ml-supervised-classification-20newsgroups/blob/main/notebooks/notebook.ipynb

## Set Up Analysis environment
```bash
export CONDA_ENV=ml-supervised-classification-20newsgroups

# Create and activate a new conda environment
conda create -n $CONDA_ENV python=3.12
conda activate $CONDA_ENV

# Install required Python packages
pip install -r requirements.txt

# Start notetebook
jupyter lab
```
