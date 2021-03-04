---

title: Adversarial-Playground- A Visualization Suite for Adversarial Sample Generation
tag:
- 4-VisualizeBench
---


### Paper [Arxiv](https://arxiv.org/abs/1706.01763)

### GitHub: [AdversarialDNN-Playground](https://github.com/QData/AdversarialDNN-Playground)

### [Poster](https://github.com/QData/AdversarialDNN-Playground/blob/master/presentation.pdf)

### Abstract
With growing interest in adversarial machine learning, it is important for machine learning practitioners and users to understand how their models may be attacked. We propose a web-based visualization tool, \textit{Adversarial-Playground}, to demonstrate the efficacy of common adversarial methods against a deep neural network (DNN) model, built on top of the TensorFlow library. Adversarial-Playground provides users an efficient and effective experience in exploring techniques generating adversarial examples, which are inputs crafted by an adversary to fool a machine learning system. To enable Adversarial-Playground to generate quick and accurate responses for users, we use two primary tactics: (1) We propose a faster variant of the state-of-the-art Jacobian saliency map approach that maintains a comparable evasion rate. (2) Our visualization does not transmit the generated adversarial images to the client, but rather only the matrix describing the sample and the vector representing classification likelihoods.

![Playground]({{ site.baseurl }}pic/adPlayground.png){:class="img-responsive"}

![pg]({{ site.baseurl }}pic/pg1.png){:class="img-responsive"}
![pg]({{ site.baseurl }}pic/pg2.png){:class="img-responsive"}

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
