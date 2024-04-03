---
categories:
- AIself
title: Beilun's PhD Defense - Fast and Scalable Joint Estimators for Learning Sparse Gaussian Graphical Models from Heterogeneous Data with Additional Knowledge
tag:
- multi-Graph-generative
- ExtraPrior
- Graph-generative
---


## PhD Defense Presentation by Beilun Wang
+  Friday, July 20, 2018 at 9:00 am in Rice 242
+  Committee Members: Mohammad Mahmoody (Chair), Yanjun Qi (Advisor), Farzad Farnoud, Xiaojin (Jerry) Zhu (University of Wisconsin–Madison), and Tingting Zhang (Statistics)

### Title: Fast and Scalable Joint Estimators for Learning Sparse Gaussian Graphical Models from Heterogeneous Data with Additional Knowledge

+  Abstract
Understanding and quantifying variable graphs from heterogeneous samples is a fundamental and urgent analysis task thanks to the data explosion in many scientific domains. Such variable graphs can significantly improve network-driven studies like understanding genetic or neural pathways or providing valuable tools for the discovery of therapeutic targets or diagnostic markers. One typical approach is to jointly estimate K different but related conditional dependency graphs through a multi-task formulation of the sparse Gaussian Graphical Model (multi-sGGM). Most current studies of multi-sGGMs, however, involve expensive and difficult non-smooth optimizations, making them difficult to scale up to many dimensions (large p) or with many contexts (large K).


In this dissertation, we aim to fill the gap and have designed a category of novel estimators that can achieve fast and scalable joint structure estimation of multiple sGGMs.
Three crucial tasks exist when learning multi-sGGMs from heterogeneous samples: (1) to enforce graph relatedness through structural norms, (2) to estimate the change of variable dependencies directly, and (3) to incorporate existing knowledge of the variable nodes or about relationships among nodes. Targeting each, our work introduces fast and parallelizable estimators that largely improves the computational efficiency of the state-of-the-art. We have conducted rigorous statistical analysis and verified that surprisingly the proposed estimators achieve the same statistical convergence rates as the state-of-art solutions that are much harder to compute. Empirically, our estimators outperform the speed of the cutting edge significantly while achieving the same or better prediction accuracy. We have implemented all proposed estimators into publicly accessible tools in the R-CRAN repository. This suite of toolboxes can help users effectively translate aggregated data into knowledge that take the form of graphs. 
 