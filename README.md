# SMILES Transformer

Toxisity prediction using latent representation of SMILES. 

## Requirement
This project requires the following libraries.

- NumPy
- Pandas
- PyTorch > 1.2
- tqdm
- RDKit

## Dataset
Canonical SMILES of 1.7 million molecules that have no more than 100 characters from Chembl24 dataset were used.  
These canonical SMILES were transformed randomly every epoch with [SMILES-enumeration](https://github.com/EBjerrum/SMILES-enumeration) by E. J. Bjerrum.

Toxicity data from https://www.kaggle.com/datasets/fanconic/smiles-toxicity were used.

## Pre-training

Pre-trained model is [here](https://drive.google.com/file/d/1LwE2BzvtDaPGYv0OR6iBjmsqoloH885N/view?usp=sharing).

## Downstream Tasks
See `experiments/` for the example codes.

```
