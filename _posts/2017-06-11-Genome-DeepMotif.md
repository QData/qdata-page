---
categories:
- AIbiomed
- AItrust
title: Deep Motif Dashboard- Visualizing and Understanding Genomic Sequences Using Deep Neural Networks
tag:
- SeqGenome
- DeepSequence
- 6-Interpret
- ToolKit
---
<a name="demo"></a>
## Tool Deep Motif Dashboard: Visualizing and Understanding Genomic Sequences Using Deep Neural Networks

### Paper: [@Arxiv](https://arxiv.org/abs/1608.03644) | [@PSB17](https://psb.stanford.edu/psb-online/proceedings/psb17/lanchantin.pdf)


### [GitHub](https://github.com/QData/DeepMotif)


### [Talk Slides](https://github.com/QData/DeepMotif/blob/master/psb_talk_slides.pdf)

### Abstract:
Deep neural network (DNN) models have recently obtained state-of-the-art prediction accuracy for the transcription factor binding (TFBS) site classification task. However, it remains unclear how these approaches identify meaningful DNA sequence signals and give insights as to why TFs bind to certain locations. In this paper, we propose a toolkit called the Deep Motif Dashboard (DeMo Dashboard) which provides a suite of visualization strategies to extract motifs, or sequence patterns from deep neural network models for TFBS classification. We demonstrate how to visualize and understand three important DNN models: convolutional, recurrent, and convolutional-recurrent networks. Our first visualization method is finding a test sequence's saliency map which uses first-order derivatives to describe the importance of each nucleotide in making the final prediction. Second, considering recurrent models make predictions in a temporal manner (from one end of a TFBS sequence to the other), we introduce temporal output scores, indicating the prediction score of a model over time for a sequential input. Lastly, a class-specific visualization strategy finds the optimal input sequence for a given TFBS positive class via stochastic gradient optimization. Our experimental results indicate that a convolutional-recurrent architecture performs the best among the three architectures. The visualization techniques indicate that CNN-RNN makes predictions by modeling both motifs as well as dependencies among them.



![demo1]({{ site.baseurl }}/pic/demo1.png){:class="img-responsive"}
![demo2]({{ site.baseurl }}/pic/demo2.png){:class="img-responsive"}
![demo3]({{ site.baseurl }}/pic/demo3.png){:class="img-responsive"}
![demo4]({{ site.baseurl }}/pic/demo4.png){:class="img-responsive"}



### Citations

```
@inproceedings{lanchantin2017deep,
  title={Deep motif dashboard: Visualizing and understanding genomic sequences using deep neural networks},
  author={Lanchantin, Jack and Singh, Ritambhara and Wang, Beilun and Qi, Yanjun},
  booktitle={PACIFIC SYMPOSIUM ON BIOCOMPUTING 2017},
  pages={254--265},
  year={2017},
  organization={World Scientific}
}
```


### Support or Contact

Having trouble with our tools? Please [contact Jack](mailto:jacklanchantin@gmail.com) and we’ll help you sort it out.
