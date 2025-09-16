---
layout: post
title: "A Comparative Study of Supervised and Self-Supervised LISTA"
date: 2025-09-16
categories: topics
published: true
---

- Type of project: Research Project/Hauptseminar/Thesis (literature review + coding)
- Contact: han.wang@tu-ilmenau.de

### Description: 
In model-based deep learning, Algorithm Unrolling turns iterative solvers for inverse problems into trainable neural networks [[1]](https://ieeexplore.ieee.org/abstract/document/9363511?casa_token=N6iJYHTBxPYAAAAA:TybTy6gOn2Izs0xffLq32HY04pOOcm0EtxyQOWyhoUmfxTjr7m0FIXNgnIwxb7zf-OCyvKqVNqo). A cornerstone of this paradigm is Learned ISTA (LISTA), an unrolled proximal-gradient network for sparse recovery that preserves the interpretability and inductive bias of the LASSO while enabling data-driven speed and accuracy gains [[2]](https://ieeexplore.ieee.org/abstract/document/10715463). This project systematically compares supervised and self-supervised (physics-guided) training for LISTA and its variants [[3]](https://par.nsf.gov/servlets/purl/10191388) [[4]](https://arxiv.org/pdf/2509.01331).

### Tasks:  
- Literature review on algorithm unrolling, signal recovery, and LISTA models.
- Implement deep unrolled neural networks for LISTA variants in the application of multichannel ultrasound imaging.
- Benchmark supervised and self-supervised LISTA training under different objectives, reporting accuracy, support recovery, and stability.

### References:  
[1] Monga, Vishal, Yuelong Li, and Yonina C. Eldar. "Algorithm unrolling: Interpretable, efficient deep learning for signal and image processing." IEEE Signal Processing Magazine 38.2 (2021): 18-44.  
[2] Wang, Han, et al. "Efficient convolutional forward modeling and sparse coding in multichannel imaging." 2024 32nd European Signal Processing Conference (EUSIPCO). IEEE, 2024.  
[3] Liu, Jialin, and Xiaohan Chen. "ALISTA: Analytic weights are as good as learned weights in LISTA." International Conference on Learning Representations (ICLR). 2019.  
[4] Nagahisa, Koshi, Ryo Hayakawa, and Youji Iiguni. "Comparison between Supervised and Unsupervised Learning in Deep Unfolded Sparse Signal Recovery." arXiv preprint arXiv:2509.01331 (2025).