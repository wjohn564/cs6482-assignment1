# CS6482 Assignment 1: Pet Image Classification

This repository contains the Jupyter Notebook for CS6482 Assignment 1. The project implements a ConvNeXt-Tiny Convolutional Neural Network (CNN) using PyTorch to classify 37 categories of cats and dogs from the Oxford-IIIT Pet dataset.

## Environment Setup
This project was developed and executed using **Anaconda** as the environment manager. 

To run this notebook, ensure you have an Anaconda environment set up with the following core dependencies:
* `pytorch` and `torchvision` (with CUDA support recommended)
* `optuna` (for hyperparameter tuning)
* `matplotlib`
* `numpy`

## Usage
Simply open and run `CS6482-Assign1-20245424.ipynb` from top to bottom. The notebook is designed to execute completely without errors. It handles downloading the dataset, preprocessing, running the three core experiments (tuning, freezing, and ablation), and calculating the final 5-fold cross-validation metrics.
