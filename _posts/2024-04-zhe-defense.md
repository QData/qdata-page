---
categories:
- AIself
title: Zhe's PhD Defense - Toward Out-Of-Distribution Generalization Of Deep Learning Models
tag:
- Tutorials
- Graph-discriminative 
- Semi-SelfLabel
- RL-Generalization 
- multi-transfer
---


## Ph.D. Dissertation Defense by Zhe Wang, 
+ Tues., 04/02/24, at 12:00PM (ET)
 
 
#### Committee:  

Matthew Dwyer, Committee Chair  (CS/SEAS/UVA)
Yanjun Qi, Advisor (CS/SEAS, SDS, SM/UVA)
Miaomiao Zhang (ECE/CS/SEAS/UVA)
Jianhui Zhou (Statistics/College/UVA)
Vicente Ordonez (CS/Rice University)
 

  
####  Title: Toward Out-Of-Distribution Generalization Of Deep Learning Models
 


+ Abstract : Deep learning models, especially deep neural networks (DNNs), perform extremely well when the testing and training distributions align. However, real-world scenarios often witness shifts in data distribution across domains, and tasks, over time, and are influenced by adversarial attacks. Such shifts from the training to testing distribution present challenges, resulting in performance degradation of DNNs. The varied testing distributions from diverse users underscore the urgent necessity to understand OOD problems and design methods to mitigate OOD generalization challenges. Therefore, this dissertation develops methods and strategies to enhance DNNs’ ability to generalize to unseen distributions. First, we focus on generalizing DNNs to unknown domains, in which no prior information about testing domains is available during training. We propose a novel optimization approach that learns principal gradients from eigenvectors of training optimization trajectories. This robust gradient design forces the training to ignore domain-dependent noise signals and updates all training domains with a robust direction covering the main components of parameter dynamics. Second, we focus on designing strategies to generalize DNNs to unseen tasks (i.e. meta-learning), for instance, a new unknown RL task with few demonstration trajectories. The main challenge is to infer the potential identity of a new task from a limited number of annotated samples. We propose modeling a new task’s identity as a stochastic variable and encoding it with a stochastic neural network. This task identity design helps meta-learning to adapt shared training knowledge to a new current task. When solving similar task generalization issues in offline RL, we further propose learning from the RL transition dynamic and reward function to capture a task’s identity. Third, deep learning models should not only perform well on clean, legitimate data distribution but also on data that has been subjected to adversarial attacks. Entering the era of large foundation models, we focus on techniques to craft adversarial attackers for jailbreaking pretrained large language models (LLMs) due to their prevalent recent adoptions. We design a new objective, which learns adversarial suffixes with much cheaper queries and higher attack success rate. The learned suffixes also demonstrate higher transferability across LLMs. In the thesis, we validate the effectiveness of our methods across image classification and completion, wealth index regression from satellite images, robotic control, real-world temperature forecasting, and natural language generation.
 
 
 
 