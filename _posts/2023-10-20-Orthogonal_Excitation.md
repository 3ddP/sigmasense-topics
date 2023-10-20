---
layout: post
title: "Comparison of Diverse Orthogonal Excitation Schemes in Ultrasound Imaging using Sparse Recovery"
date: 2023-05-31
categories: topics
published: true
---

- Type of project: WIP
- Contact: ozan.cakiroglu@izfp.fraunhofer.de

![image]({{ site.baseurl }}/assets/images/measurement_area.png)

In the field of ultrasound imaging, our objective is to detect specific defects that are assumed to be distinct and occupy a relatively small area within the overall measurement area. By making this assumption, we can effectively utilize sparse signal recovery algorithms in the receiver to accurately identify the location of these defects. However, the accuracy of these algorithms can be significantly improved by minimizing the correlation between received signals by employing transmit beamforming or receive beamforming. Another hypothetic idea of realizing that the aim is to use orthogonally precoded pulse shapes instead of conventional pulse shapes.

In this research, our aim is to increase the spatial resolution of the ultrasound images by employing orthogonal excitation. However, the question of which orthogonal codes (Golay codes, Hadamard codes, Barker codes etc.) would comply with our target of minimizing spatial resolution is still in need of investigation which is the ultimate goal of this project. 

#### Project Phases
* Literature survey on different orthogonal excitation codes, fast pulse-echo ultrasound imaging using sparse recovery, sparsity promoting algorithms...
* Formulation and implementation of orthogonally precoded transmission pulse shapes together with mathematical model of the received signal
* Performance comparison between implementations employing different orthogonal pulse shapes.
* Documentation

#### Related Works
* Schiffner, Martin F., and Georg Schmitz. "Fast pulse-echo ultrasound imaging employing compressive sensing." 2011 IEEE International Ultrasonics Symposium. IEEE, 2011.
* D. Bujoreanu, Y. M. Benane, H. Liebzott, B. Nicolas, O. Basset and D. Friboulet, "A Resolution Enhancement Technique for Ultrafast Coded Medical Ultrasound," 2018 26th European Signal Processing Conference (EUSIPCO), Rome, Italy, 2018.
#### Requirements
* Solid knowledge in linear algebra and signal processing
* Good knowledge in estimation theory, compressed sensing
* Python programming

#### Contact Information
- M.Sc. Ozan Çakıroğlu
- ozan.cakiroglu@izfp.fraunhofer.de
