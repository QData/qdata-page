---

title: Adversarial-Playground Paper  Appear @ VizSec17  
tag:
- 4-VisualizeBench
- ToolKit
---

<a name="play"></a>


### Revised Version2 Paper [Arxiv](http://arxiv.org/abs/1708.00807)

### Revised Title: Adversarial-Playground: A Visualization Suite Showing How Adversarial Examples Fool Deep Learning

### Publish @ The IEEE Symposium on Visualization for Cyber Security (VizSec) 2017 -[ULR](http://ieeexplore.ieee.org/document/8062202/)

### [Presentation](https://github.com/QData/AdversarialDNN-Playground/blob/master/presentation.pdf)

### [![Recorded Video of Andrew's Presentation]({{ site.baseurl }}/pic/VIStalk.png)](https://vimeo.com/242155607)

### GitHub: [AdversarialDNN-Playground](https://github.com/QData/AdversarialDNN-Playground)

### Abstract

Recent studies have shown that attackers can force deep learning models to
misclassify so-called "adversarial examples": maliciously generated images
formed by making imperceptible modifications to pixel values. With growing
interest in deep learning for security applications, it is important for
security experts and users of machine learning to recognize how learning
systems may be attacked. Due to the complex nature of deep learning, it is
challenging to understand how deep models can be fooled by adversarial
examples. Thus, we present a web-based visualization tool,
Adversarial-Playground, to demonstrate the efficacy of common adversarial
methods against a convolutional neural network (CNN) system.
Adversarial-Playground is educational, modular and interactive. (1) It enables
non-experts to compare examples visually and to understand why an adversarial
example can fool a CNN-based image classifier. (2) It can help security experts
explore more vulnerability of deep learning as a software module. (3) Building
an interactive visualization is challenging in this domain due to the large
feature space of image classification (generating adversarial examples is slow
in general and visualizing images are costly). Through multiple novel design
choices, our tool can provide fast and accurate responses to user requests.
Empirically, we find that our client-server division strategy reduced the
response time by an average of 1.5 seconds per sample. Our other innovation, a
faster variant of JSMA evasion algorithm, empirically performed twice as fast
as JSMA and yet maintains a comparable evasion rate.
  Project source code and data from our experiments available at:
  [GitHub](https://github.com/QData/AdversarialDNN-Playground)  


### Citations

```
@inproceedings{norton2017adversarial,
  title={Adversarial-Playground: A visualization suite showing how adversarial examples fool deep learning},
  author={Norton, Andrew P and Qi, Yanjun},
  booktitle={Visualization for Cyber Security (VizSec), 2017 IEEE Symposium on},
  pages={1--4},
  year={2017},
  organization={IEEE}
}
```


### Support or Contact

Having trouble with our tools? Please [contact Andrew Norton](mailto:apn4za@virginia.edu) and we’ll help you sort it out.
