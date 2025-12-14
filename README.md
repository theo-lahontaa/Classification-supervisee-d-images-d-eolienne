# Image Classification Project (PyTorch)

This repository contains a binary image classification project implemented in **PyTorch**. It includes a logistic regression baseline, a simple neural network model, full training and evaluation loops, and visualization of misclassified images. A final model class is provided in the required format for **automated grading**.

## Project Content
- Data loading with `ImageFolder`
- Preprocessing: `Resize`, `ToTensor`, `Normalize`
- Logistic regression baseline (`nn.Linear`)
- MLP model with one hidden layer and ReLU
- Training and validation loops
- Test evaluation and confusion matrix
- Display of misclassified images
- Template `final_model` class + loading of `final_model_trained_weights.pth`

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

Install with:
```
pip install torch torchvision matplotlib numpy
```

## Notes
- The final evaluation block follows the structure expected for automated correction.
- The dataset and trained weights are not included in the repository.
