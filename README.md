# 🧠 Brain Tumor Classification with Machine Learning

**Automated detection of glioma, meningioma, and pituitary tumors from MRI scans using deep learning and explainable AI**

## 📌 Overview
This project implements a medical AI pipeline for:
- **3-Class Tumor Classification** (Glioma, Meningioma, Pituitary)
- **Multi-Model Comparison**:
  - Custom 3D CNN
  - Transfer Learning (ResNet50, EfficientNet)
  - Traditional ML (SVM with radiomics features)
- **Explainability**: Grad-CAM heatmaps and SHAP analysis

## 🚀 Quick Start

### Installation
```bash
git clone https://github.com/yourusername/BrainTumor-ML-Classification.git
cd BrainTumor-ML-Classification
pip install -r requirements.txt  # tensorflow, opencv, scikit-learn
