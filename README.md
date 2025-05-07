# Discrete VAE with Concrete (Gumbel-Softmax) Relaxation

This project implements and extend a **Discrete Variational Autoencoder (dVAE)** using the **Concrete (Gumbel-Softmax) distribution** to enable gradient-based optimization of discrete latent variables, as proposed in the [Concrete Distribution paper](https://arxiv.org/abs/1611.00712).

## 📄 Summary

- The full background, methodology, experiments, and analysis are detailed in the attached **PDF report**.
- The core method is based on applying Concrete relaxation in VAEs for MNIST digit reconstruction.
- For code and runnable examples, see the attached **Jupyter Notebook** (`.ipynb`) — a light version due to file size limits, including **one experiment per section**.

## 📁 Files Included

- `Paper Summarization & Practical Part Report.pdf` – Full explanation, experimental results, and figures.
- `Practical_Part_Code_Light_Version.ipynb` – Minimal runnable notebook covering one experiment per idea.
