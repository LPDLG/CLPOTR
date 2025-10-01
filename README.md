# Brushstrokes Beyond the Scroll: MAE-Enhanced Cultural-Aware Outpainting Method of Chinese Landscape Painting

🎨 **CLPOTR** is a novel framework for image outpainting tailored to the unique characteristics of Chinese landscape paintings. It integrates cultural awareness into deep learning techniques to preserve the multi-scale brushstroke layering, complex mountain hierarchies, and unified artistic conception inherent in traditional art.

## 🧠 Overview

Chinese landscape painting presents unique challenges for image outpainting due to its:
- Long-range spatial continuity
- Local brushstroke consistency
- Stylistic coherence

**CLPOTR** addresses these challenges through a culturally-informed design based on the **Masked Autoencoder** architecture.

## ✨ Key Features

- **Three-Phase Progressive Mask Dilation Training**  
  Guides the model to learn compositional rules from local to global scales.

- **Dual-Domain Large-Kernel Convolution–Attention Expansion Module (LKEA)**  
  Enhances long-range dependency modeling and ink feature representation.

- **Dual-Branch Heterogeneous Attention Decoder**  
  Enables collaborative modeling of macroscopic structures and microscopic brushstrokes.

- **Multi-Scale Patch Smoothing Module**  
  Reduces boundary artifacts and improves visual quality.

- **Joint Loss Function**  
  Balances fidelity and stylistic coherence across scales.

## 📊 Performance

CLPOTR achieves superior results compared to existing methods on:
- **FID (Fréchet Inception Distance)**
- **IS (Inception Score)**
- **PSNR (Peak Signal-to-Noise Ratio)**

It demonstrates high fidelity and strong cross-style generalization on classical landscape paintings and murals.

---

> 📢 The source code of this project will be released after the official publication of our paper. Stay tuned!
