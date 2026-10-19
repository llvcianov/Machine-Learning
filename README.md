# ML — Machine Learning

Coursework for **Machine Learning (ML)**, Master's Degree in Computer Engineering, University of Naples Federico II.

## Mini-competitions

Three in-class, Kaggle-style mini-competitions. Each folder has my own solution (KNIME workflow or notebook), my submission, and the competition's info/description PDF where available — not the train/test datasets themselves.

- [`MC1/`](MC1) — [unina-machine-learning-24-25-mc-1](https://www.kaggle.com/competitions/unina-machine-learning-24-25-mc-1)
- [`MC2/`](MC2) — [unina-machine-learning-24-25-mc-2](https://www.kaggle.com/competitions/unina-machine-learning-24-25-mc-2)
- [`MC3/`](MC3) — [unina-machine-learning-24-25-mc-3](https://www.kaggle.com/competitions/unina-machine-learning-24-25-mc-3) ([`uninaml.ipynb`](MC3/uninaml.ipynb), an image classification task)

The `.knwf` files in `MC1/` and `MC2/` are [KNIME](https://www.knime.com/) workflow exports;

## Lab exercises

[`Esercitazioni_Lab/`](Esercitazioni_Lab) collects the lab sessions:

- `.knar`/`.knwf` files — KNIME exercises (`.knar` bundles a whole exported workflow group/session, `.knwf` is a single workflow) covering regression, handling missing values, and Kaggle-style submission preparation.
- [`DeepLearning/`](Esercitazioni_Lab/DeepLearning) — PyTorch notebooks: an MLP on the sklearn digits dataset, CNN feature extraction and a binary classifier with model-interpretability methods (Integrated Gradients, Occlusion) on a dogs-vs-wolves dataset, a conditional GAN on a flowers dataset, and two notebooks adapted from public tutorials (a GAN tutorial and PyTorch's official DCGAN tutorial) rather than written from scratch.

Datasets are not included.
