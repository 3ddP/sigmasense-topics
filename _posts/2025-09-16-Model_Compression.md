---
layout: post
title: "Convolutional Model Compression for Multichannel Imaging"
date: 2025-09-16
categories: topics
published: true
---

- Type of project: Research Project/Hauptseminar/Thesis (literature review + coding)
- Contact: han.wang@tu-ilmenau.de

### Description: 
Recent advances in Machine Learning have led to increasingly large models, creating significant challenges for both hardware resources and algorithmic design. In multichannel imaging, the forward model mapping the signal of interest to the measurement data is typically high-dimensional and computationally demanding. To address this issue, we have developed efficient convolutional forward models [[1]](https://ieeexplore.ieee.org/abstract/document/10715463). Nevertheless, the resulting convolutional kernels are often large and mostly sparse, presenting substantial opportunities for model compression [[2]](https://ieeexplore.ieee.org/abstract/document/9043731). In this project, we aim to explore efficient model compression techniques, such as knowledge distillation [[3]](https://arxiv.org/pdf/2006.05525) and low-rank convolutional decomposition, to accelerate both forward mapping and backward imaging in (ultrasound) multichannel imaging systems.

### Tasks:
- Literature review on convolutional model compression methods.
- Understand the efficient convolutional models of multichannel imaging and implement machine learning-based model compression schemes.
- Evaluate algorithm performance using appropriate metrics, compare with SOTA/baseline algorithms, and perform the ablation analysis.

### References: 
[1] Wang, Han, et al. "Efficient convolutional forward modeling and sparse coding in multichannel imaging." 2024 32nd European Signal Processing Conference (EUSIPCO). IEEE, 2024.  
[2] Deng, Lei, et al. "Model compression and hardware acceleration for neural networks: A comprehensive survey." Proceedings of the IEEE 108.4 (2020): 485-532.   
[3] Gou, Jianping, et al. "Knowledge distillation: A survey." International journal of computer vision 129.6 (2021): 1789-1819.