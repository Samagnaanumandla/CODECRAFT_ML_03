# Cats vs Dogs Image Classification Using SVM

This project implements a Support Vector Machine (SVM) to classify images of cats and dogs from the Kaggle Dogs vs Cats dataset.

## Dataset
The images are taken from the Kaggle Dogs vs Cats dataset. Images are preprocessed by resizing to 64x64 pixels and converting to grayscale.

## Methodology
- Images are loaded and labeled based on filename prefixes (`cat` or `dog`).
- Images are flattened into 1D arrays to be used as features.
- The dataset is split into train and test sets.
- A linear kernel SVM is trained on the training data.
- The model is evaluated on the test set with accuracy reported.

