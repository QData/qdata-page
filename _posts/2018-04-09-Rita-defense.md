---
categories:
- AIbiomed
title: Rita's PhD Defense - Fast and Interpretable Classification of Sequential Data in Biology
tag:
- EpiGenome
- DeepSequence
- 6-Interpret
- Tutorials
---


## Ph.D. Dissertation Defense by Ritambhara Singh
+  Monday, April 9, 2018 at 12:00PM in Rice 504.

### Title: Fast and Interpretable Classification of Sequential Data in Biology

+ Committee Members: Yanjun Qi (Advisor), Mary Lou Soffa (Chair), Gabriel Robins, Mazhar Adli (UVA Biochemistry and Molecular Genetics), Christina Leslie (Minor Representative- Memorial Sloan Kettering Cancer Center)

### Abstract: 

Biological sciences are rapidly becoming data intensive. Between 100 million to 2 billion human genomes are estimated to be sequenced by the year 2025, far exceeding the growth of big data domains like Astronomy, YouTube, and Twitter.  Majority of these biological datasets are sequential in nature, representing the human genome as well as measurements of activity taking place around it. Analyzing this enormous repository of sequential data is both urgent and essential to understand genetic diseases and drug development. Data-driven approaches like machine learning have shown significant progress in analyzing the existing data. However, the state-of-the-art machine learning techniques face two hard challenges in this domain: (1) Interpretability of the predictions for better insights, and (2) Slow computation due to expanding search space of sequential patterns. In this dissertation, we aim to solve these two challenges by improving two popular machine learning models: Deep Neural Networks (DNNs) and String Kernel with Support Vector Machines (SK-SVM). 

+[Challenge(1):] DNNs can handle large sequential datasets accurately and in an efficient manner. However, DNNs have widely been viewed as ‘black boxes' due to the complex, multi-layer structure, making them hard to understand. We implement a unified DNN architecture to model and to interpret features in an end-to-end manner. The proposed design is not only accurate, but it also provides better interpretation than state-of-the-art feature visualization methods such as saliency maps. 

+[Challenge (2):] SK-SVM methods achieve high accuracy and have theoretical guarantees with limited labeled training samples. However, current implementations run extremely slow when we increase the dictionary size or allow more mismatches. We present a novel algorithmic implementation for calculating Gapped k-mer string Kernel using Counting (GaKCo). This method is fast, scalable and naturally parallelizable. Empirically, GaKCo performs up to 100 times faster than the state-of-the-art SK-SVM method across multiple biological sequential datasets. 