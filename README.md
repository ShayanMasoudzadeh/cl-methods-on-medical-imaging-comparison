# Continual Learning in Medical Imaging

This repository contains a comparative study of three continual learning approaches:
- Regularization-based (EWC)
- Replay-based methods (Experience Replay)
- Dynamic model approaches (Multi-Head model)

All methods are evaluated on a medical imaging dataset from MedMNIST using the Avalanche continual learning framework.

## Repository Structure

- `notebooks/`: Jupyter notebooks for training and evaluation
- `results/`: Saved evaluation metrics (JSON)
- `figures/`: Plots used for comparison

## Methods

Each method is trained under identical conditions:
- Same dataset
- Same model architecture
- Same number of experiences
- Same evaluation protocol

## Requirements

See `requirements.txt`.

## Notes

This project was developed as part of a Computer Vision course's project.
