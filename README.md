# Rotation Invariance in CNN vs Vision Transformer

This project compares the performance of Convolutional Neural Networks (CNN) and Vision Transformers (ViT) in recognizing rotated images from MNIST and Fashion-MNIST datasets.

## Overview

- Implemented and tested CNN and ViT models using PyTorch.
- Investigated rotation invariance by training on unrotated data and evaluating on rotated datasets.
- Analyzed classification accuracy, confusion matrices, and sample predictions.

## Dataset

- **MNIST**: Handwritten digits (0–9)
- **Fashion-MNIST**: Clothing category images

## Methodology

1. Train CNN and ViT models on unrotated training datasets.
2. Generate rotated test datasets (various rotation angles).
3. Compare model robustness by analyzing performance drop under rotation.

## Results

- CNN performed well for small rotations but degraded with large rotations.
- ViT showed more stable performance across rotation ranges.

## Requirements

Install dependencies:

```bash
pip install -r requirements.txt
```
