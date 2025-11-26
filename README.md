# Ablation Study for Subnetworks Emerging from RL Finetuning

An experiment designed as part of the [MAT1510](https://sites.google.com/view/mat1510/fall-2025?authuser=0) final project. 

## Setup

First, create a virtual environment or run using your local installation of Python. Then, install the requirements using
```bash
pip install -r requirements.txt
```

## The Notebooks

The `subnetworks.ipynb` was used to explore which threshold showed high update sparsity.

The `ablation.ipynb` is the main notebook used to create the altered models and where the main experiments were run to explore the effects of resetting specifc weights tied to the identified subnetwork back to the base model.

The `evaluation.ipynb` is an old notebook used to run similar experiments with zeroed out weights instead. The results were uninsightful so it has been discarded, but the notebook is still included to look at if interested.