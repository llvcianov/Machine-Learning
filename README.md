# ML — Machine Learning

Coursework for **Machine Learning (ML)**, Master's Degree in Computer Engineering, University of Naples Federico II.

## Mini-competitions

Three in-class, Kaggle-style mini-competitions. These were run as private Kaggle InClass competitions for the course — their Kaggle pages require course enrollment to view, so each one's Overview/Data page is reproduced locally instead. Each folder has that writeup, my own solution (KNIME workflow or notebook), and my submission — not the train/test datasets themselves.

- [`MC1/`](MC1) — [Land Cover Classification from Satellite Data](MC1/README.md): predicting land cover type from Sentinel-2 multispectral features, via KNN after normalization and correlation-based feature filtering.
- [`MC2/`](MC2) — [Solar Irradiance Forecasting](MC2/README.md): a regression task predicting PV solar irradiance from meteorological variables.
- [`MC3/`](MC3) — [Cancer Identification in Breast Cells](MC3/README.md): binary classification (benign/malignant) of fluorescence-microscopy cell images via CNN transfer learning.

The `.knwf` files in `MC1/` and `MC2/` are [KNIME](https://www.knime.com/) workflow exports;

## Lab exercises

[`Esercitazioni_Lab/`](Esercitazioni_Lab) collects the lab sessions:

- `.knar`/`.knwf` files — KNIME exercises (`.knar` bundles a whole exported workflow group/session, `.knwf` is a single workflow) covering regression, handling missing values, and Kaggle-style submission preparation.
- [`DeepLearning/`](Esercitazioni_Lab/DeepLearning) — PyTorch notebooks: an MLP on the sklearn digits dataset, CNN feature extraction and a binary classifier with model-interpretability methods (Integrated Gradients, Occlusion) on a dogs-vs-wolves dataset, a conditional GAN on a flowers dataset, and two notebooks adapted from public tutorials (a GAN tutorial and PyTorch's official DCGAN tutorial) rather than written from scratch.

Datasets are not included.
