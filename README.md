# CNN Robustness under Non-IID Data (CIFAR-10)

## Overview
This project evaluates the robustness of Convolutional Neural Networks (CNNs) under non-IID data distributions and strict computational constraints.

## Objective
To analyse how distribution shifts (IID vs non-IID) affect model generalisation performance under limited training time.

## Dataset
- CIFAR-10 dataset
- Controlled training constraint (1-minute limit on T4 GPU)

## Model
- Lightweight CNN architecture
- Cross-entropy loss
- Adam optimizer
- Regularisation techniques applied

## Results
- Achieved 70%+ test accuracy
- Analysed performance degradation under non-IID settings
- Documented robustness trade-offs under compute constraints

## Key Insights
- Non-IID distribution significantly affects generalisation.
- Constrained training environments require architecture and optimisation trade-offs.
