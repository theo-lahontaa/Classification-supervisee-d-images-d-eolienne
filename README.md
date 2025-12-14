# Image Classification Project (PyTorch)

This repository contains a supervised image classification project developed in the context of a Master 2 course on deep learning. The work includes baseline models, convolutional architectures, full training/evaluation loops, and a final report summarizing the experiments.

## Project Content
- Data loading with `ImageFolder`
- Preprocessing: `Resize`, `ToTensor`, `Normalize`
- Logistic regression baseline (`nn.Linear`)
- Simple MLP model
- Convolutional models (ResNet18, ResNet34, EfficientNet, DenseNet) tested on small and large datasets
- Training loops, validation monitoring, confusion matrix
- Misclassified image visualization
- Regularization methods: data augmentation, dropout, label smoothing, early stopping
- Final model based on **ResNet18** with tuned hyperparameters

## Report
A short PDF report summarizing the experimental setup, results, and model selection is included:
- *Classification supervisée d’images d’éoliennes – Rapport de projet* :contentReference[oaicite:1]{index=1}

## Dataset Structure
```
data/
├── train/class0, class1
├── val/class0, class1
└── test/class0, class1
```

## Dependencies
```
torch
torchvision
matplotlib
numpy
```

Install:
```
pip install torch torchvision matplotlib numpy
```

## Notes
- The final model template follows the format required for automated grading.
- The dataset and trained weights are not included in the repository.
