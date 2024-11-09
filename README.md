
# QMNIST Neural Network Model Training and Hyperparameter Tuning

## Overview

This project trains and optimizes a neural network on the QMNIST dataset to classify digits. The steps include model setup, performance evaluation, modifications, and hyperparameter tuning to achieve improved accuracy.

## Project Steps

1. **Dataset Preparation**:
   - Loaded and visualized the QMNIST dataset.
   - Prepared data loaders for training and testing.

2. **Initial Model Setup**:
   - Built a base neural network model from scratch.
   - Measured baseline prediction accuracy on training and test datasets.

3. **Model Modification**:
   - Chose to either add an additional Dense layer of 128 nodes or increase an existing layer to 256 nodes.
   - **Hypothesis**: Documented the expected effect of this modification on model performance.

4. **Modified Model Training**:
   - Trained the modified model and compared its accuracy to the base model.

5. **Hyperparameter Tuning**:
   - Experimented with optimizers, loss functions, dropout rates, and activation functions.
   - Analyzed the performance impact of each adjustment.

## Results

- **Base Model Accuracy**: (Include your base accuracy results).
- **Modified Model Accuracy**: (Summarize modified model results).
- **Impact of Hyperparameter Tuning**: (Provide a brief summary of how tuning influenced performance).

## Conclusion

Summarized the findings, including insights from model modifications and hyperparameter tuning.

## Requirements

To run this notebook, install the following packages:
```bash
pip install -r requirements.txt
