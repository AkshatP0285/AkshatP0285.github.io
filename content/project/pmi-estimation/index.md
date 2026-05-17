---
title: 'PMI Estimation using Forensic Iris Images'
summary: Deep learning pipelines for post-mortem interval estimation using CNNs, DINO, and CLIP with forensic iris imagery.
tags:
  - Computer Vision
  - Deep Learning
  - Forensic Science
  - Transfer Learning
  - Biometrics
date: '2024-05-01T00:00:00Z'

external_link: ''

image:
  caption: 'Forensic Iris Analysis for PMI Estimation'
  focal_point: Smart

links: []

url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

slides: ''
---

## Project Overview

This is my **bachelor's thesis project** at IISER Bhopal, developing advanced deep learning approaches for post-mortem interval (PMI) estimation using forensic iris images. The work investigates transfer learning and self-supervised learning paradigms for this challenging forensic science application.

## Research Objectives

- Estimate PMI from iris image characteristics
- Develop robust models resistant to domain shift
- Leverage self-supervised learning for improved generalization
- Enable practical forensic science applications

## Technical Approach

### 1. **Deep Learning Architectures**

**CNNs (Convolutional Neural Networks)**
- Traditional supervised learning baseline
- Custom architectures optimized for iris analysis
- Local feature extraction and classification

**DINO (Self-Supervised Learning)**
- Self-supervised vision transformer training
- Learned representations without labeled data
- Improved feature robustness and generalization

**CLIP (Vision-Language Models)**
- Multi-modal learning combining vision and text
- Zero-shot and few-shot inference capabilities
- Semantic understanding of iris characteristics

### 2. **Cross-Dataset Transfer Learning**

**Training Dataset**: 180K synthetic iris images
- Large-scale synthetic data generation
- Domain-specific augmentation strategies
- Controlled variation for robust learning

**Evaluation**: Real forensic iris datasets
- Transfer to real-world forensic images
- Assessment of domain gap handling
- Practical applicability validation

### 3. **PMI Prediction Methodology**

- Feature extraction from iris morphology
- Temporal degradation modeling
- Regression or classification frameworks
- Multi-stage refinement approaches

## Key Innovations

1. **Large-Scale Synthetic Dataset**: 180K images for transfer learning
2. **Multi-Model Ensemble**: Combines CNNs, DINO, and CLIP strengths
3. **Self-Supervised Approach**: Reduced reliance on labeled forensic data
4. **Domain Adaptation**: Effective transfer from synthetic to real data

## Technologies

- **Deep Learning**: PyTorch, TensorFlow
- **Models**: Vision Transformers, DINO, OpenAI CLIP
- **Computer Vision**: OpenCV, scikit-image
- **Data Generation**: Synthetic iris generation pipelines

## Impact & Applications

- **Forensic Science**: Improved PMI estimation accuracy
- **Legal Applications**: Supporting forensic investigations
- **Research**: Advances in transfer learning for specialized domains
- **Methodology**: Framework applicable to other biometric forensic applications

## Academic Recognition

This work was developed as a comprehensive bachelor's thesis demonstrating:
- Deep understanding of multiple deep learning paradigms
- Practical application to real-world forensic challenges
- Advanced implementation and evaluation skills

## Supervisor

Completed under guidance at IISER Bhopal with focus on forensic science applications of modern AI.
