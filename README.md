# bento-manuscript
Analyses to reproduce figures in the Bento manuscript.

# How to Run

## Install `bento-tools` package

Analyses depend on the `bento-tools` python package. First install dependencies by following [installation instructions](https://bento-tools.readthedocs.io/en/v2.0.0/installation.html) before using pip to install version `2.1.0a0`. Be sure this exact version is installed for reproducibility.

```{bash}
pip install bento-tools==2.1.0a0 matplotlib==3.4 scanpy==1.9.1 statannotations leidenalg decoupler==0.14.0 omnipath
```

## `notebooks`
All analyses are stored under the `notebooks` folder.
> Note: data paths need to be set properly

- `figure-analysis` - notebooks to reproduce figures and supplementary figures in the manuscript
- `subcellular-classifier/` - training and evaluating localization pattern classifiers (RNAforest)
- `data-ingestion/` - data preprocessing/formatting for downstream analysis with `bento-tools`


## `data`
- annotated data for training and evaluating RNAforest classifiers
- processed seqFISH+, MERFISH, and Molecular Cartography datasets can be downloaded directly with the `bento-tools` Python package

## `models`
This contains intermediate outputs from hyperparameter optimization, model training, and fine-tuning. Final models are part of the `bento-tools` package. Read package [documentation](https://bento-tools.readthedocs.io/) to understand how the models are used.

