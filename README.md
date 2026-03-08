# Deep Learning and Foundation Models

This repository contains my coursework and experiments for deep learning and foundation models using Jupyter notebooks on **CSC.fi infrastructure**, specifically the **Puhti supercomputer**.

## Contents

- `Assignment 1- Ali Khalessi.ipynb`  
  Compares MLP performance on the MNIST dataset using **3, 5, and 10 hidden layers** with PyTorch.

- `Assignment 2.ipynb`  
  Trains and evaluates **ResNet18** on a **dogs vs cats** image classification task using PyTorch and transfer learning.

## Assignment 1: MNIST MLP Depth Comparison

In this notebook, PyTorch is used to train Multi-Layer Perceptron (MLP) models on the MNIST dataset.  
The main goal is to compare how the number of hidden layers affects performance.

### Task
- Use PyTorch on **CSC Puhti**
- Train MLP models with:
  - 3 hidden layers
  - 5 hidden layers
  - 10 hidden layers
- Compare test accuracy and runtime

### Main result
The **5-layer model** achieved the best overall performance in this experiment, while runtime differences were small in the GPU-based run on Puhti.

---

## Assignment 2: ResNet18 on Dogs vs Cats

In this notebook, a **ResNet18** model is trained on a dog and cat image dataset.  
The workflow includes dataset preparation, model training, validation, and sample prediction visualization.

### Task
- Prepare the dataset in `ImageFolder` format
- Train and evaluate ResNet18
- Use **CSC.fi / Puhti** resources for the experiment

### Main result
The notebook demonstrates a complete image classification pipeline using transfer learning with ResNet18 on Puhti.

---

## Environment

These notebooks were developed and run on **CSC.fi** computing resources, mainly on the **Puhti supercomputer**, using:

- Python 3
- PyTorch
- Torchvision
- Jupyter Notebook / JupyterLab
- GPU resources when available

## How to run

1. Open the notebook in JupyterLab or Jupyter Notebook
2. Make sure PyTorch and required libraries are installed
3. Run the cells in order from top to bottom

## Notes

- Some paths in the notebooks are configured for the **CSC Puhti** environment
- Dataset files may need to be downloaded or placed in the correct directory before running
- Results may vary slightly between runs

## Author

**Ali Khalessi**
