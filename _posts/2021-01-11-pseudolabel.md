---
categories:
- AIself
title: Curriculum Labeling- Self-paced Pseudo-Labeling for Semi-Supervised Learning
tag:
- Semi-SelfLabel 
---




### Title: Curriculum Labeling- Self-paced Pseudo-Labeling for Semi-Supervised Learning" 


#### at the Thirty-Fifth AAAI Conference on Artificial Intelligence (AAAI-21) (acceptance rate: 21%)) 


#### authors: Paola Cascante-Bonilla, Fuwen Tan, Yanjun Qi, Vicente Ordonez

### Paper [Arxiv](https://arxiv.org/abs/2001.06001)


### Abstract
In this paper we revisit the idea of pseudo-labeling in the context of semi-supervised learning where a learning algorithm has access to a small set of labeled samples and a large set of unlabeled samples. Pseudo-labeling works by applying pseudo-labels to samples in the unlabeled set by using a model trained on the combination of the labeled samples and any previously pseudo-labeled samples, and iteratively repeating this process in a self-training cycle. Current methods seem to have abandoned this approach in favor of consistency regularization methods that train models under a combination of different styles of self-supervised losses on the unlabeled samples and standard supervised losses on the labeled samples. We empirically demonstrate that pseudo-labeling can in fact be competitive with the state-of-the-art, while being more resilient to out-of-distribution samples in the unlabeled set. We identify two key factors that allow pseudo-labeling to achieve such remarkable results (1) applying curriculum learning principles and (2) avoiding concept drift by restarting model parameters before each self-training cycle. We obtain 94.91% accuracy on CIFAR-10 using only 4,000 labeled samples, and 68.87% top-1 accuracy on Imagenet-ILSVRC using only 10% of the labeled samples. The code is available at following https URL


#### [code](https://github.com/uvavision/Curriculum-Labeling)

### Citations

```
@misc{grigsby2020measuring,
      title={Measuring Visual Generalization in Continuous Control from Pixels}, 
      author={Jake Grigsby and Yanjun Qi},
      year={2020},
      eprint={2010.06740},
      archivePrefix={arXiv},
      primaryClass={cs.LG}
}
```


### Support or Contact

Having trouble with our tools? Please [contact Jake](mailto:jcg6dn@virginia.edu) and we’ll help you sort it out.
