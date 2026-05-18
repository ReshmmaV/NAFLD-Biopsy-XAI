# NAFLD Biopsy XAI

![Python](https://img.shields.io/badge/Python-3.10-blue)
![PyTorch](https://img.shields.io/badge/PyTorch-DeepLearning-red)
![MedicalAI](https://img.shields.io/badge/Medical-AI-green)
![XAI](https://img.shields.io/badge/XAI-ExplainableAI-success)

## Explainable AI-based Deep Learning Framework for the Classification of Non-Alcoholic Fatty Liver Disease Using Liver Biopsy Images

This repository presents an Explainable AI-driven deep learning framework for automated classification and staging of Non-Alcoholic Fatty Liver Disease (NAFLD) using liver biopsy histopathology images.

The framework performs multi-class classification of liver biopsy images using multiple Convolutional Neural Network (CNN) architectures and integrates Explainable AI (XAI) methods to improve model interpretability and clinical trustworthiness.

---

# Overview

Non-Alcoholic Fatty Liver Disease (NAFLD) is one of the most prevalent chronic liver diseases worldwide, affecting approximately 25.24% of the global population and nearly 38% of the Indian population.

NAFLD progresses through multiple pathological stages including:
- Steatosis
- Inflammation
- Cellular ballooning
- Fibrosis
- Cirrhosis

Histopathological examination of liver biopsy images remains the gold standard for diagnosing and staging NAFLD.

However:
- Histological variations between disease stages are often subtle
- Manual assessment is time-consuming
- Inter-observer variability affects consistency
- Misclassification may impact treatment planning

This work proposes an automated Explainable AI-based deep learning framework to assist pathologists in accurate and consistent NAFLD staging using liver biopsy images.

---

# Abstract

Non-alcoholic fatty liver disease (NAFLD) is one of the most prevalent chronic liver diseases affecting about 25.24% of the population worldwide. It is one of the growing health concerns affecting millions of people worldwide. In India, approximately 38% of the population is affected by this condition.

NAFLD is a progressive disease; it starts with simple steatosis, then progresses to hepatic steatosis, fibrosis, and cirrhosis. Histopathological analysis of liver biopsy remains the definitive gold standard for diagnosing and staging NAFLD.

The major challenge lies in the subtle visual differences between disease stages, leading to inter-observer variability among clinicians.

To address this clinical gap, this work develops an automated deep learning framework for multi-class classification of liver biopsy images using four prominent CNN architectures:
- RegNetX-200MF
- ResNet-50
- Inception-V3
- VGG-16

All models were trained on the same dataset of 3,857 liver biopsy images to ensure fair comparison.

Experimental results demonstrated that RegNetX-200MF achieved superior performance with:
- Overall Accuracy: 95.34%
- Macro F1 Score: 0.9537

The model outperformed:
- ResNet-50: 93.3%
- Inception-V3: 91.83%
- VGG-16: 90.92%

The advanced architecture of RegNetX-200MF effectively captured subtle textual and morphological features necessary for differentiating complex pathological states.

The proposed framework has the potential to serve as a reliable AI-assisted diagnostic tool for pathologists by improving diagnostic speed, consistency, and accuracy.

---

# Keywords

- Non-Alcoholic Fatty Liver Disease
- NAFLD
- Liver Histopathology
- Liver Biopsy
- Deep Learning
- Explainable AI
- Medical Imaging
- RegNetX
- Histopathological Classification
- Biomedical Image Analysis

---

# Technical Contributions

## Deep Learning Framework
- Multi-class liver biopsy classification
- Comparative CNN architecture evaluation
- Automated disease staging pipeline

## CNN Architectures Evaluated
- RegNetX-200MF
- ResNet-50
- Inception-V3
- VGG-16

## Explainable AI
- Model interpretability
- Visual explanation generation
- Pathology-focused feature localization

## Clinical Decision Support
- Automated staging assistance
- Reduced inter-observer variability
- AI-assisted pathology workflow

---

# Dataset Information

| Property | Value |
|---|---|
| Total Images | 3,857 |
| Classification Type | Multi-Class |
| Domain | Liver Histopathology |

---

# Model Performance

| Model | Accuracy |
|---|---|
| RegNetX-200MF | 95.34% |
| ResNet-50 | 93.3% |
| Inception-V3 | 91.83% |
| VGG-16 | 90.92% |

---

# Best Model

## RegNetX-200MF

### Performance
- Accuracy: 95.34%
- Macro F1 Score: 0.9537

### Advantages
- Better capture of subtle histological patterns
- Improved morphological feature extraction
- Superior multi-class discrimination

---

# Technologies Used

- Python
- PyTorch
- TensorFlow
- RegNetX-200MF
- ResNet-50
- Inception-V3
- VGG-16
- OpenCV
- NumPy
- Pandas
- Matplotlib
- Explainable AI (XAI)

---

# Workflow

1. Liver biopsy image preprocessing
2. Dataset augmentation
3. CNN model training
4. Multi-class classification
5. Model evaluation
6. Explainable AI analysis
7. Performance comparison

---

# Explainable AI Results

Explainable AI methods demonstrated that the model focuses on:
- steatosis regions
- fibrosis patterns
- cellular ballooning structures
- inflammatory regions
- histopathological texture variations

These visual explanations improve model transparency and support trustworthy clinical AI deployment.

---

# Applications

- AI-assisted pathology
- Liver disease staging
- Histopathology image analysis
- Clinical decision support systems
- Biomedical image analysis
- Explainable medical AI

---

# Future Scope

- Multi-center clinical validation
- Whole-slide image analysis
- Transformer-based pathology models
- Real-time pathology assistance
- Multi-modal liver disease analysis
- Clinical deployment pipelines

---

# Authors

- Reshmma Vijayakumar
- Kethan Sai Vuppalapati
- Namasivaya Naveen S

---

# License

This repository is intended for academic and research purposes only.

---
