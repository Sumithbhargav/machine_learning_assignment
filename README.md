# Understanding Variational Autoencoders: Learning Structured Latent Representations for Generative Modelling

This repository contains the code and tutorial for an experiment exploring **Variational Autoencoders (VAEs)** and their ability to learn structured latent representations for generative modelling. The project compares a **standard autoencoder** with a **variational autoencoder** using the MNIST handwritten digit dataset. The aim of the tutorial is to demonstrate how probabilistic regularisation in VAEs produces smoother latent spaces and enables meaningful data generation.

## Project Overview
The tutorial investigates three key aspects of representation learning:
- reconstruction performance of autoencoders
- structure of the learned latent space
- generative capability through latent sampling

Two models are implemented and compared:
1. **Standard Autoencoder** – learns compressed representations by minimising reconstruction loss.
2. **Variational Autoencoder (VAE)** – introduces a probabilistic latent distribution and KL divergence regularisation to produce a structured latent space.

## Dataset
The experiments use the **MNIST dataset**, which consists of grayscale images of handwritten digits (0–9) with a resolution of 28×28 pixels.  
To reduce training time while preserving the distribution of the data, the tutorial uses:
- 20,000 training samples  
- 5,000 test samples  


## Requirements
The implementation uses Python and the following libraries:
- PyTorch
- torchvision
- NumPy
- Matplotlib
- scikit-learn

Install the dependencies using:

pip install torch torchvision numpy matplotlib scikit-learn

## Running the Code
1. Clone the repository:
git clone <repository-link>

2. Open the notebook:
jupyter notebook sumith_ml_code.ipynb

3. Run the notebook cells sequentially to reproduce the experiments, figures, and results described in the tutorial.
