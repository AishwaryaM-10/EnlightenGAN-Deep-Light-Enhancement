# EnlightenGAN: Deep Light Enhancement

This repository contains an implementation of **EnlightenGAN**, an unsupervised GAN-based model for low-light image enhancement. The project demonstrates how deep learning can enhance image visibility without paired supervision.

## 🔍 Project Overview

Low-light conditions often result in poor image quality. This project applies EnlightenGAN to enhance such images using a data-driven, unsupervised generative adversarial network.

### ✨ Key Features

- End-to-end unsupervised learning using GANs
- Works without paired low-light and normal-light image datasets
- Generator and discriminator architecture as proposed in the EnlightenGAN paper
- Visual comparison of enhanced outputs vs. original inputs

---

## 📦 Requirements

Install dependencies using:

pip install -r requirements.txt

# EnlightenGAN: Deep Light Enhancement Without Paired Supervision

This repository contains an implementation of **EnlightenGAN**, a GAN-based unsupervised model for enhancing low-light images. The model leverages deep learning to improve image clarity and visibility without requiring paired low-light and normal-light training images.

---

## 🔍 Project Summary

In this project, we successfully explored and implemented an image enhancement model focused on improving image quality through various testing and evaluation metrics.

The model effectively processes images, handles edge cases, and meets performance expectations for memory usage and inference time. We addressed the limitations of previous methods by integrating additional layers—**LIME** and **GAMMA**—which significantly reduced issues like:
- Color distortion
- Noise
- Overexposure

These enhancements enabled better illumination correction and contrast boosting, delivering **natural and visually appealing results** across a variety of lighting conditions.

---

## 📊 Evaluation

The model was rigorously evaluated using key image quality metrics:

| Metric | Value (Avg) |
|--------|-------------|
| PSNR   | 14          |
| SSIM   | 0.9         |
| NIQE   | 0.7         |

- **LIME and GAMMA layers** were pivotal in handling extreme cases.
- Results validated robustness and high-quality enhancement across standard and edge-case scenarios.
- Inference time and memory usage remained within optimal limits.

---

## 📁 Repository Contents

| File | Description |
|------|-------------|
| `gan_clean.ipynb` | Clean version of the notebook (no output cells) |
| `gan_outputs.ipynb` | Contains only extracted outputs (for visual evaluation) |
| `gan.ipynb` *(optional)* | Original full notebook with code and output cells |
| `README.md` | This documentation file |

---

## 📦 Setup & Requirements

Install dependencies:

pip install -r requirements.txt

