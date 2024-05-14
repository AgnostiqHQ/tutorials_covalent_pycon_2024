# Zero-Data AI Model Foundry

This repository contains a [*Covalent Cloud*](https://www.covalent.xyz/cloud/) Jupyter notebook that creates an AI model foundry for zero-data model fine-tuning.

## Context

The example here was prepared for [PyCon 2024](https://us.pycon.org/2024/) in Pittsburgh, PA.

## Instructions

### To follow along

Open the Jupyter notebook in your browser (or in an IDE).

```
jupyter notebook zero-data-model-foundry.ipynb
```

### To run the notebook

**Running the notebook requires a [Covalent Cloud account](https://app.covalent.xyz/register).**

1. Log in and copy your API key from the Covalent Cloud dashboard. Paste the key as the value of the `CC_API_API` variable in the `environment.yml` file.

2. Create a conda environment using the `environment.yml` file.

```
conda env create -f environment.yml
```

3. Active the environment.

```
conda activate covalent-pycon-2024
```

4. Open the Jupyter notebook in your browser (or in an IDE).

```
jupyter notebook zero-data-model-foundry.ipynb
```
