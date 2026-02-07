
## 🔬 Research Publication

This project has been extended into a **research paper**, which has been **accepted for presentation and publication** at the following IEEE conference:

**Conference:** IEEE ITHREECTCON 2026  
**Status:** Accepted  
**Year:** 2026  

The research paper presents the detailed methodology, experimental analysis, and evaluation of the proposed DnCNN-based chest X-ray denoising approach, demonstrating its effectiveness in improving image quality under low-dose imaging conditions.

📌 *This repository contains the implementation and experimental results corresponding to the published research work.*

### 👨‍💻 Team Members
- Varun Terdal   
**Guide:** Dr. Uday Kulkarni  

---

## 📖 Project Overview

Chest X-ray images often suffer from noise due to low-dose imaging conditions, which degrades diagnostic quality.  
This project focuses on **deep learning–based image denoising** using the **DnCNN (Denoising Convolutional Neural Network)** to effectively remove noise while preserving important anatomical details.

The model leverages **residual learning** to predict noise components and subtract them from noisy X-ray images, resulting in high-quality denoised outputs suitable for medical analysis.

---

## ❗ Problem Statement

Low-dose chest X-ray images contain significant noise that reduces clarity and affects diagnostic accuracy.  
Traditional denoising methods often blur critical structures. Hence, an advanced deep learning approach is required to reduce noise **without losing medical details**.

---

## 🎯 Objectives

- Remove **Poisson noise** from low-dose chest X-ray images  
- Enhance image clarity while preserving anatomical structures  
- Apply **DnCNN with residual learning** for effective denoising  
- Improve quantitative image quality metrics such as PSNR and SSIM  

---

## 🛠️ Proposed Work

1. Use clean chest X-ray images from the **NIH dataset**
2. Simulate low-dose imaging by adding **Poisson noise**
3. Feed noisy images into the **DnCNN model**
4. Predict noise using **residual learning**
5. Subtract predicted noise to obtain denoised images
6. Evaluate results using standard image quality metrics

---

## 🧠 Methodology

1. Input chest X-ray image  
2. Add noise to simulate low-dose conditions  
3. Pass noisy image through CNN-based DnCNN  
4. Model learns noise distribution (residual learning)  
5. Noise is subtracted from input image  
6. Output denoised chest X-ray image  

---

## 🏗️ Model Architecture

- Convolutional Layers  
- Batch Normalization  
- ReLU Activation  
- Residual Learning Framework  

The network is trained to predict the **noise component**, not the clean image directly, improving convergence and denoising performance.

---

## 📊 Results & Performance Metrics

| Metric | Value |
|------|------|
| **PSNR** | 33.25 dB |
| **MSE** | 4.76 × 10⁻⁴ |
| **SSIM** | 0.91 |

✔ Significant noise reduction  
✔ Preserved anatomical structures  
✔ Improved image quality without blurring  

---

## 🖼️ Sample Results

The following results demonstrate:
- Original clean image  
- Noisy image  
- Denoised output using DnCNN  

> Noise is effectively removed while maintaining clinical details.

## 🧪 Tools & Technologies Used

- Python  
- Google Colab / Jupyter Notebook  
- TensorFlow / Keras  
- NumPy  
- OpenCV  
- Matplotlib  

---

## 📂 Project Structur
