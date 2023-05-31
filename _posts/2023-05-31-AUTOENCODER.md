---
layout: post
title: "Autoencoder-based Detection of Optimum Transmission Parameters in Ultrasound Imaging using Sparse Recovery"
date: 2023-05-31
categories: topics
---

<img src="/assets/images/measurement_area.png" alt= “” width="400" height="400" style="float: right;">

In the field of ultrasound imaging, our objective is to detect specific defects that are assumed to be distinct and occupy a relatively small area within the overall measurement area. By making this assumption, we can effectively utilize sparse signal recovery algorithms in the receiver to accurately identify the location of these defects. However, the accuracy of these algorithms can be significantly improved by minimizing the mutual coherence of the sensing matrix through conventional numerical optimization methods or by leveraging neural network techniques.

In this project, our ultimate aim is to develop and implement an autoencoder network. This network will be fed with sparse compressibility values of the material, and it will endeavor to determine the optimal values of transmitted pulse amplitudes and delays. By optimizing these parameters, we seek to enhance the accuracy and speed of defect detection in ultrasound imaging.

#### Project Phases
* Literature survey on the fast pulse-echo ultrasound imaging using sparse recovery, sparsity promoting algorithms, autoencoder networks...
* Formulation and implementation of the autoencoder network including mathematical model of the received signal
* Performance comparison between different sparsity promoting algorithms.
* Documentation

#### Related Works
* Schiffner, Martin F., and Georg Schmitz. "Fast pulse-echo ultrasound imaging employing compressive sensing." 2011 IEEE International Ultrasonics Symposium. IEEE, 2011.

#### Requirements
* Solid knowledge in linear algebra and signal processing
* Good knowledge in estimation theory, compressed sensing, machine learning
* Python programming

#### Contact Information
- M.Sc. Ozan Çakıroğlu
- ozan.cakiroglu@izfp.fraunhofer.de
