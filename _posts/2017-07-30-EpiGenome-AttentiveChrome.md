---
categories:
- AIbiomed
title: NeurIPS - AttentiveChrome-Deep Attention Model to Understand Gene Regulation by Selective Attention on Chromatin
tag:
- EpiGenome
- DeepSequence
- 6-Interpret
- ToolKit
---

## Tool AttentiveChrome: Attend and Predict: Using Deep Attention Model to Understand Gene Regulation by Selective Attention on Chromatin

### Paper:  [@Arxiv](https://arxiv.org/abs/1708.00339) + Published at [NIPS2017]
(https://papers.nips.cc/paper/7255-attend-and-predict-understanding-gene-regulation-by-selective-attention-on-chromatin.pdf)


### [GitHub](https://github.com/QData/AttentiveChrome)

### [talk slides PDF](https://github.com/QData/AttentiveChrome/blob/master/20171126-PNNL-AttentiveChrome.pdf)


### [poster PDF](https://github.com/QData/AttentiveChrome/blob/master/NIPS%20poster.pdf)


### Abstract:
The past decade has seen a revolution in genomic technologies that enable a flood of genome-wide profiling of chromatin marks. Recent literature tried to understand gene regulation by predicting gene expression from large-scale chromatin measurements. Two fundamental challenges exist for such learning tasks: (1) genome-wide chromatin signals are spatially structured, high-dimensional and highly modular; and (2) the core aim is to understand what are the relevant factors and how they work together? Previous studies either failed to model complex dependencies among input signals or relied on separate feature analysis to explain the decisions. This paper presents an attention-based deep learning approach; we call AttentiveChrome, that uses a unified architecture to model and to interpret dependencies among chromatin factors for controlling gene regulation. AttentiveChrome uses a hierarchy of multiple Long short-term memory (LSTM) modules to encode the input signals and to model how various chromatin marks cooperate automatically. AttentiveChrome trains two levels of attention jointly with the target prediction, enabling it to attend differentially to relevant marks and to locate important positions per mark. We evaluate the model across 56 different cell types (tasks) in human. Not only is the proposed architecture more accurate, but its attention scores also provide a better interpretation than state-of-the-art feature visualization methods such as saliency map.
Code and data are shared at www.deepchrome.net

![attentiveChrome]({{ site.baseurl }}/pic/aChrome1.png){:class="img-responsive"}

![attentiveChrome]({{ site.baseurl }}/pic/aChrome2.png){:class="img-responsive"}

### Citations

```
@inproceedings{singh2017attend,
  title={Attend and Predict: Understanding Gene Regulation by Selective Attention on Chromatin},
  author={Singh, Ritambhara and Lanchantin, Jack and Sekhon, Arshdeep  and Qi, Yanjun},
  booktitle={Advances in Neural Information Processing Systems},
  pages={6769--6779},
  year={2017}
}

```


### Support or Contact


Having trouble with our tools? Please [contact Rita](mailto:rs3zz@virginia.edu) and we’ll help you sort it out.
