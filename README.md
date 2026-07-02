# Masked-Autoencoder-MAE-for-Image-Reconstruction

---

# Overview

This repository contains the implementation of a **Masked Autoencoder (MAE)** based on the Vision Transformer (ViT) architecture for image reconstruction. The project trains a self-supervised learning model to reconstruct missing image patches and evaluates its performance using image quality metrics. An interactive **Gradio** interface is also included for testing the trained model.

---

# Features

- Vision Transformer (ViT)-based Masked Autoencoder
- Random patch masking strategy
- Image reconstruction from masked inputs
- Self-supervised learning
- Mixed precision training (AMP)
- Interactive Gradio interface
- Performance evaluation using PSNR and SSIM
- Visualization of original, masked, and reconstructed images

---

# Model Architecture

The implementation includes:

- Patch Embedding Layer
- Transformer Encoder
- Transformer Decoder
- Random Patch Masking
- Image Reconstruction Head

---

# Dataset

The model is trained using the **Tiny ImageNet-200** dataset.

Dataset structure:

```
tiny-imagenet-200/
├── train/
├── val/
├── test/
├── wnids.txt
└── words.txt
```

---

# Evaluation Metrics

The reconstructed images are evaluated using:

- PSNR (Peak Signal-to-Noise Ratio)
- SSIM (Structural Similarity Index)

---

# Technologies Used

- Python
- PyTorch
- Torchvision
- NumPy
- Matplotlib
- Pillow
- tqdm
- Gradio
- scikit-image

---

# Results

The notebook provides:

- Model training
- Validation results
- Original image visualization
- Masked image visualization
- Reconstructed image visualization
- PSNR and SSIM evaluation
- Interactive Gradio demo

---

# Requirements

Install the required libraries before running the notebook.

```bash
pip install torch torchvision
pip install numpy matplotlib pillow
pip install tqdm
pip install gradio
pip install scikit-image
```

---

# How to Run

1. Open the notebook:

```
AI_ASS02_22F_3343,3326.ipynb
```

2. Install all required libraries.

3. Download or mount the Tiny ImageNet dataset.

4. Run all notebook cells sequentially.

5. After training, launch the Gradio interface to reconstruct custom images.

---

# Project Workflow

1. Load Tiny ImageNet dataset
2. Preprocess images
3. Generate random image masks
4. Train the Masked Autoencoder
5. Reconstruct masked images
6. Evaluate reconstruction quality using PSNR and SSIM
7. Test the model through the Gradio interface

---

# Learning Outcomes

- Understanding self-supervised learning
- Implementing Vision Transformer (ViT)
- Learning Masked Autoencoder (MAE) architecture
- Image reconstruction using deep learning
- Evaluating reconstruction quality
- Deploying AI models with Gradio

---

# Future Improvements

- Train on larger datasets
- Increase model depth
- Improve reconstruction quality
- Fine-tune hyperparameters
- Deploy the application online

---

# Author

**Eman Fatima**
