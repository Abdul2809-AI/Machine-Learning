# 🩺 Medical Image Translation & Evaluation using CycleGAN Variants

[![Made with Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)](https://www.python.org/)
[![Framework](https://img.shields.io/badge/PyTorch-2.x-red?logo=pytorch)](https://pytorch.org/)
[![Kaggle Dataset](https://img.shields.io/badge/Dataset-Kaggle-blue?logo=kaggle)](https://www.kaggle.com/your-dataset-link)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

---

## 📌 Overview

This repository contains the complete implementation of my **thesis research** on *Benign vs Malignant Medical Image Translation* using three variants of **CycleGAN**:

1. **Simple CycleGAN**
2. **Transfer Learning Simplified CycleGAN (TL-S-CycleGAN) with ResNet-50 Discriminator**
3. **TL-S-CycleGAN with VGG-16 Discriminator**

The project focuses on **synthetic medical image generation** and **comparative evaluation** using both classification and image quality metrics.

---

## 📂 Dataset

We use the **[Kaggle Medical Image Dataset](https://www.kaggle.com/your-dataset-link)** containing benign and malignant medical images.  
The dataset is preprocessed to work directly with PyTorch’s `ImageFolder` format.

---

## 📁 Folder Structure

```plaintext
├── 📁 training/
│   ├── simple_cyclegan.ipynb
│   ├── tls_cyclegan_resnet50.ipynb
│   ├── tls_cyclegan_vgg16.ipynb
│
├── 📁 testing/
│   ├── test_simple_cyclegan.ipynb
│   ├── test_tls_cyclegan_resnet50.ipynb
│   ├── test_tls_cyclegan_vgg16.ipynb
│
├── 📁 metrics/
│   ├── classification_metrics_fcn_visuals.ipynb
│   ├── image_quality_metrics_comparison.ipynb
│
├── README.md
├── LICENSE

## 📊 Evaluation Metrics

### **Classification Performance**
- **Accuracy**
- **Precision**
- **Recall**
- **F1-Score**

### **Fully Convolutional Network (FCN) Metrics**
- **IoU (Intersection over Union)**
- **PCA (Pixel Classification Accuracy)**
- **PPA (Pixel Precision Accuracy)**

### **Image Quality Metrics**
- **SSIM (Structural Similarity Index Measure)**
- **PSNR (Peak Signal-to-Noise Ratio)**
- **MSE (Mean Squared Error)**

---

## 💡 Key Insights
- **TL-S-CycleGAN** models outperform the simple CycleGAN in **image quality** and **classification metrics**.
- **VGG-16 based discriminator** excels in preserving fine textures.
- **ResNet-50 based discriminator** offers a good balance between generation and classification performance.
- The evaluation pipeline ensures **both qualitative and quantitative** comparison between models.

