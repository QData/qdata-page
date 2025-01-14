---
categories:
- AItrust
title: Weilin's PhD Defense - Improving Robustness of Machine Learning Models using Domain Knowledge
tag:
- 1-Evasion
- 4-VisualizeBench
- 2-Detection
- Tutorials
---

## Ph.D. Dissertation Defense by Weilin Xu

#### Title: Improving Robustness of Machine Learning Models using Domain Knowledge

+ 11 am, Monday, April 15, 2019, at Rice 504.

####  Committee Members: 
Vicente Ordonezan (Committee Chair), 
David Evans, Advisor
Yanjun Qi, Advisor
Homa Alemzadeh
Patrick McDaniel


#### Abstract 
Although machine learning techniques have achieved great success in many areas, such as computer vision, natural language processing, and computer security, recent studies have shown that they are not robust under attack. A motivated adversary is often able to craft input samples that force a machine learning model to produce incorrect predictions, even if the target model achieves high accuracy on normal test inputs. This raises great concern when machine learning models are deployed for security-sensitive tasks. 

This dissertation aims to improve the robustness of machine learning models by exploiting domain knowledge. While domain knowledge has often been neglected due to the power of automatic representation learning in the deep learning era, we find that domain knowledge goes beyond a given dataset of a task and helps to (1) uncover weaknesses of machine learning models, (2) detect adversarial examples and (3) improve the robustness of machine learning models.

First, we design an evolutionary algorithm-based framework, \emph{Genetic Evasion}, to find evasive samples. We embed domain knowledge into the mutation operator and the fitness function of the framework and achieve 100% success rate in evading two state-of-the-art PDF malware classifiers. Unlike previous methods, our technique uses genetic programming to directly generate evasive samples in the problem space instead of the feature space, making it a practical attack that breaks the trust of black-box machine learning models in a security application.

Second, we design an ensemble framework, \emph{Feature Squeezing}, to detect adversarial examples against deep neural network models using simple pre-processing. We employ domain knowledge on signal processing that natural signals are often redundant for many perception tasks. Therefore, we can squeeze the input features to reduce adversaries' search space while preserving the accuracy on normal inputs. 
We use various squeezers to pre-process an input example before it is fed into a model. The difference between those predictions is often small for normal inputs due to redundancy, while the difference can be large for adversarial examples. We demonstrate that \emph{Feature Squeezing} is empirically effective and inexpensive in detecting adversarial examples for image classification tasks generated by many algorithms.

Third, we incorporate simple pre-processing with certifiable robust training and formal verification to train provably-robust models. We formally analyze the impact of pre-processing on adversarial strength and derive novel methods to improve model robustness. Our approach produces accurate models with verified state-of-the-art robustness and advances the state-of-the-art of certifiable robust training methods.

We demonstrate that domain knowledge helps us understand and improve the robustness of machine learning models. Our results have motivated several subsequent works, and we hope this dissertation will be a step towards implementing robust models under attack.