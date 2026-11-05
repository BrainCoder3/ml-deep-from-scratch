# ml-deep-from-scratch

Machine learning and deep learning projects from my self-study path
*"Comprendre et construire l'intelligence artificielle"*. The goal is to understand
each method by implementing it by hand first, then compare it with a library.

## Projects

| Project | Topic | Status |
| ------- | ----- | ------ |
| P1 | Data audit pipeline with pandas (missing values, duplicates, distributions) | done |
| P2 | Linear regression and gradient descent written in NumPy | done |
| P3 | Handwritten digits with classic ML | [separate repository](https://github.com/BrainCoder3/handwritten-digits-classification) |
| P4 | Unsupervised learning: PCA and clustering | in progress |
| P5 | PyTorch lab | planned |

## What each project shows

- **P1 - Data audit**: a reusable function that loads a CSV, reports size, missing values
  and duplicates, then plots a histogram and a curve.
- **P2 - Linear regression**: batch gradient descent on synthetic data
  (`y = 3x + 2 + noise`), train / validation / test split, learning rate comparison
  chosen on validation only, and a constant baseline.
- **P4 - PCA**: dimensionality reduction on the digits dataset, image reconstruction
  and explained variance for several numbers of components.

## Run it

```bash
python -m venv .venv
source .venv/bin/activate        # Windows: .venv\Scripts\activate
pip install -r requirements.txt
jupyter notebook
```

## Repository layout

```
P1_data_audit/
P2_linear_regression/
P4_unsupervised_pca/
```

Each folder contains one notebook.
