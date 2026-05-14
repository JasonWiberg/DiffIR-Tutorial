
# DiffIR Tutorial: Diffusion-Based Image Restoration

This repository contains a Google Colab tutorial [![Open In Colab](https://colab.research.google.com/drive/12iiyVn7V4nbyBr5S_89eJY89cG4WPuXE#scrollTo=Ztvf_81JHxqB) demonstrating how to load, run, and fine-tune the DiffIR (Diffusion Image Restoration) model for real-world super-resolution (realSR). DiffIR is designed to restore degraded images (blurry, noisy, low resolution, etc.) using diffusion-based methods. This tutorial dives deep into the source code and model architecture.

<img width="1294" height="333" alt="download" src="https://github.com/user-attachments/assets/61d7d9a4-c120-4049-9f7b-fe344018aa2e" />


## Introduction

This tutorial provides a detailed walkthrough of the DiffIR model, including its architecture, training procedure, and how to apply it for image restoration. We cover everything from initial setup in a Colab environment to performing inference and fine-tuning the model on custom datasets.

## References

- **DiffIR GitHub**: [https://github.com/Zj-BinXia/DiffIR](https://github.com/Zj-BinXia/DiffIR)
- **arXiv Paper**: [https://arxiv.org/abs/2303.09472](https://arxiv.org/abs/2303.09472)


## How to Run This Tutorial

1.  **Open in Google Colab**: Click the "Open in Colab" badge (or equivalent) at the top of the notebook.
2.  **Upload Pre-Trained Model**: Choose a DiffIR model, and upload the file to the base content directory.
3.  **Upload Images**: Upload your low quality images to a folder called 'lq_images'
