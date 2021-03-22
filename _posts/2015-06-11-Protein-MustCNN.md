---
categories:
- AIbiomed
- AIself
title:  MUST-CNN- A Multilayer Shift-and-Stitch Deep Convolutional Architecture for Sequence-based Protein Structure Prediction
tag:
- Protein
- DeepSequence 
- Represent-ngram
- multi-transfer
---

<a name="mustcnn"></a>
## Tool MUST-CNN: A Multilayer Shift-and-Stitch Deep Convolutional Architecture for Sequence-based Protein Structure Prediction

### [Paper](https://arxiv.org/abs/1605.03004)


### [GitHub](https://github.com/DeepLearning4BioSeqText/Paper16-AAAI-MUST-CNN)


### [Talk Slides ](https://github.com/DeepLearning4BioSeqText/Paper16-AAAI-MUST-CNN/blob/master/paper/2016-AAAIt.pdf)

### Abstract
Predicting protein properties such as solvent accessibility and secondary structure from its primary amino acid sequence is an important task in bioinformatics. Recently, a few deep learning models have surpassed the traditional window based multilayer perceptron. Taking inspiration from the image classification domain we propose a deep convolutional neural network architecture, MUST-CNN, to predict protein properties. This architecture uses a novel multilayer shift-and-stitch (MUST) technique to generate fully dense per-position predictions on protein sequences. Our model is significantly simpler than the state-of-the-art, yet achieves better results. By combining MUST and the efficient convolution operation, we can consider far more parameters while retaining very fast prediction speeds. We beat the state-of-the-art performance on two large protein property prediction datasets.



![must1]({{ site.baseurl }}/pic/mustcnn1.png){:class="img-responsive"}
![must2]({{ site.baseurl }}/pic/mustcnn2.png){:class="img-responsive"}
![must3]({{ site.baseurl }}/pic/mustcnn3.png){:class="img-responsive"}
![must4]({{ site.baseurl }}/pic/mustcnn4.png){:class="img-responsive"}


### Citations

```
@inproceedings{lin2016must,
  title={MUST-CNN: a multilayer shift-and-stitch deep convolutional architecture for sequence-based protein structure prediction},
  author={Lin, Zeming and Lanchantin, Jack and Qi, Yanjun},
  booktitle={Proceedings of the Thirtieth AAAI Conference on Artificial Intelligence},
  pages={27--34},
  year={2016},
  organization={AAAI Press}
}
```




### Support or Contact

Having trouble with our tools? Please [contact Jack](mailto:jacklanchantin@gmail.com) and we’ll help you sort it out.
