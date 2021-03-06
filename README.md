# bento-manuscript
Analyses to reproduce figures in the Bento manuscript.

# How to Run
All analyses are stored under the `notebooks` folder. Run in numbered order within each subfolder.
- `subcellular-classifier`: training and evaluating localization pattern classifiers
- `seqfish-plus`: generate seqfish and RBP related figures in the paper
- `merfish`: generate merfish figures and supplementary figures

## `data`
All files needed to run the notebooks can be found here. The seqFISH+ and MERFISH datasets are downloaded through the `bento-tools` Python package. [Follow the installation instructions for the package here](https://bento-tools.readthedocs.io/).

## `figures`
Main figures generated by the notebooks are generally stored here.

## `models`
This contains intermediate outputs from hyperparameter optimization, model training, and fine-tuning. Final models are part of the `bento-tools` package. Read package [documentation](https://bento-tools.readthedocs.io/) to understand how the models are used.

