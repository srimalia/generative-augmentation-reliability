# On the Reliability of Generative Augmentation: A Wasserstein-Based Theoretical and Empirical Study

**Authors:** Chathurika S. Abeykoon, Mathias Nthiani Muia, and Mallory Goldstein

This repository contains the Python implementation and supporting materials for our study of conditional generative augmentation in imbalanced classification.

## Methods

We compare Conditional GAN (CGAN), Conditional Wasserstein GAN with Gradient Penalty (CWGAN-GP), Random Oversampling (ROS), and SMOTE using Random Forest and multilayer perceptron classifiers.

## Datasets

The experiments use four publicly available datasets from the UCI Machine Learning Repository:

- Bank Marketing
- Credit Card Default
- Forest Cover Type
- Wine Quality (Red)

## Reproducibility

The experiments use ten random seeds (44–53), stratified training/validation/test splits (60%/20%/20%), and validation-based augmentation-strength selection.

The `code/` directory contains the experimental scripts and analysis notebooks. The `results/` directory contains supporting numerical outputs.

## Requirements

Python and the dependencies specified in `requirements.txt`.

## Publication

Manuscript: *On the Reliability of Generative Augmentation: A Wasserstein-Based Theoretical and Empirical Study*.

Journal of Data Science (under revision).
