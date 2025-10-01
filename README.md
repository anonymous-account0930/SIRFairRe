# Fair Dimension Reduction Experiments

This repository contains Jupyter notebooks that reproduce the main experimental results from our NeurIPS 2025 submission on fair dimension reduction.

We evaluate our proposed methods on four widely studied benchmark datasets from the fair ML literature:
- Adult Income (UCI)
- COMPAS Recidivism (ProPublica)
- German Credit (UCI)
- CelebA (image dataset)

## 📁 Repository Contents

Each notebook corresponds to one dataset:
- `Adult UCI Experiments.ipynb`
- `COMPAS UCI Experiments.ipynb`
- `GERMAN UCI Experiments.ipynb`
- `CelebA Experiments.ipynb`

These notebooks include all preprocessing steps, model fitting procedures, and visualizations needed to replicate the experimental figures and tables in the paper.

## Requirements

- Python ≥ 3.8
- `numpy`, `pandas`, `scikit-learn`, `matplotlib`, `seaborn`
- For CelebA: `torch`, `torchvision`

You can install dependencies with:

```bash
pip install -r requirements.txt
```

## Data Access
We do not include datasets in this repository. To reproduce the experiments, please download the datasets as follows:

Adult (UCI):
https://archive.ics.uci.edu/ml/datasets/adult

COMPAS:
https://github.com/propublica/compas-analysis

German Credit:
https://archive.ics.uci.edu/ml/datasets/statlog+(german+credit+data)

CelebA:
http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html

Each notebook includes guidance on how to download and organize the corresponding dataset.


