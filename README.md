# EnlightenGAN: Deep Light Enhancement Without Paired Supervision

This repository contains an implementation of **EnlightenGAN**, a GAN-based unsupervised model for enhancing low-light images. The model leverages deep learning to improve image clarity and visibility without requiring paired low-light and normal-light training images.

---
### ✨ Key Features

- End-to-end unsupervised learning using GANs
- Works without paired low-light and normal-light image datasets
- Generator and discriminator architecture as proposed in the EnlightenGAN paper
- Visual comparison of enhanced outputs vs. original inputs

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

## 📦 Setup & Requirements

#### 1. Clone the repository:

     git clone https://github.com/AishwaryaM-10/EnlightenGAN-Deep-Light-Enhancement.git

     cd EnlightenGAN-Deep-Light-Enhancement

#### 2. Install dependencies:

     pip install -r requirements.txt

## 🌍 Real-World Applications

The EnlightenGAN model has broad applicability in real-world scenarios where low-light image clarity is critical:

- **Surveillance Systems:** Improve visibility in night-time CCTV footage for better threat detection.
- **Autonomous Vehicles:** Enhance vision in dim environments to assist in safe navigation.
- **Medical Imaging:** Brighten low-light images from diagnostic equipment without adding noise.
- **Mobile Photography:** Integrate with smartphone cameras for night mode or low-light shooting.
- **Satellite & Aerial Imaging:** Boost clarity in satellite or drone images captured under poor lighting.
- **Underwater Exploration:** Enhance images taken in deep-sea missions where light is scarce.
- **Disaster Response:** Improve imagery for search-and-rescue operations conducted in dark or smoke-filled environments.

These applications showcase the potential of GAN-based enhancement in both consumer and critical mission domains.


## 👥 Contributors

This project was completed as a team effort. We thank all members for their valuable collaboration throughout the development process.

- Aishwarya M
- [Abhijeet Rachagoudar]
- [Ashutosh Gebise]
- [LalitKumar Solapure]






