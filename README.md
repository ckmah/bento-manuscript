# bento-manuscript
Analyses to reproduce figures in the Bento manuscript.

# How to Run

## Install `bento-tools` package

Analyses depend on the `bento-tools` python package. See the [installation instructions](https://bento-tools.readthedocs.io/en/v2.0.0a/installation.html) to install version `2.0.0a0`. Be sure this exact version is installed for reproducibility.

## `notebooks`
All analyses are stored under the `notebooks` folder.
> Note: data paths need to be set properly

- All primary analyses described in main figures for each dataset respectively:
    - `Seqfish_analysis.ipynb`
    - `Merfish_analysis.ipynb`
    - `Cardiomyocytes_analysis.ipynb`
- `subcellular-classifier/` - training and evaluating localization pattern classifiers (RNAforest)
- `data-ingestion/` - data preprocessing/formatting for downstream analysis with `bento-tools`


## `data`
The processed seqFISH+, MERFISH, and Molecular Cartography datasets are downloaded through the `bento-tools` Python package. Files for training/evaluation of RNAforest classifiers can be found in this folder.

## `models`
This contains intermediate outputs from hyperparameter optimization, model training, and fine-tuning. Final models are part of the `bento-tools` package. Read package [documentation](https://bento-tools.readthedocs.io/) to understand how the models are used.

