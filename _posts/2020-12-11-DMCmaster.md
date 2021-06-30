---
categories:
- AIself
title: NeurIPS - Measuring Visual Generalization in Continuous Control from Pixels
tag:
- RL-Generalization 
- multi-transfer
---

<a name="RL-Generalization"></a>

### Title: Measuring Visual Generalization in Continuous Control from Pixels

+ authors: Jake Grigsby, Yanjun Qi

### Paper [Arxiv](https://arxiv.org/abs/2010.06740)

### Code [Here](https://github.com/QData/dmc_remastered)

### Abstract
Self-supervised learning and data augmentation have significantly reduced the performance gap between state and image-based reinforcement learning agents in continuous control tasks. However, it is still unclear whether current techniques can face a variety of visual conditions required by real-world environments. We propose a challenging benchmark that tests agents' visual generalization by adding graphical variety to existing continuous control domains. Our empirical analysis shows that current methods struggle to generalize across a diverse set of visual changes, and we examine the specific factors of variation that make these tasks difficult. We find that data augmentation techniques outperform self-supervised learning approaches and that more significant image transformations provide better visual generalization \footnote{The benchmark and our augmented actor-critic implementation are open-sourced @ this https URL)


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
