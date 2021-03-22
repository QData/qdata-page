---
categories:
- AIbiomed
title: Graph Convolutional Networks for Epigenetic State Prediction Using Both Sequence and 3D Genome Data
tag:
- EpiGenome
- SeqGenome
- DeepSequence
- BioGraph
---

<a name="lamp"></a>

### Title: Graph Convolutional Networks for Epigenetic State Prediction Using Both Sequence and 3D Genome Data


### Paper [Bioinformatics](https://academic.oup.com/bioinformatics/article/36/Supplement_2/i659/6055904)


### GitHub: [https://github.com/QData/ChromeGCN](https://github.com/QData/ChromeGCN)

![demo1]({{ site.baseurl }}/pic/chromeGCN.png){:class="img-responsive"}



### Abstract

##### Motivation
Predictive models of DNA chromatin profile (i.e. epigenetic state), such as transcription factor binding, are essential for understanding regulatory processes and developing gene therapies. It is known that the 3D genome, or spatial structure of DNA, is highly influential in the chromatin profile. Deep neural networks have achieved state of the art performance on chromatin profile prediction by using short windows of DNA sequences independently. These methods, however, ignore the long-range dependencies when predicting the chromatin profiles because modeling the 3D genome is challenging.

#####  Results
In this work, we introduce ChromeGCN, a graph convolutional network for chromatin profile prediction by fusing both local sequence and long-range 3D genome information. By incorporating the 3D genome, we relax the independent and identically distributed assumption of local windows for a better representation of DNA. ChromeGCN explicitly incorporates known long-range interactions into the modeling, allowing us to identify and interpret those important long-range dependencies in influencing chromatin profiles. We show experimentally that by fusing sequential and 3D genome data using ChromeGCN, we get a significant improvement over the state-of-the-art deep learning methods as indicated by three metrics. Importantly, we show that ChromeGCN is particularly useful for identifying epigenetic effects in those DNA windows that have a high degree of interactions with other DNA windows.




### Citations

```
@article{10.1093/bioinformatics/btaa793,
    author = {Lanchantin, Jack and Qi, Yanjun},
    title = "{Graph convolutional networks for epigenetic state prediction using both sequence and 3D genome data}",
    journal = {Bioinformatics},
    volume = {36},
    number = {Supplement_2},
    pages = {i659-i667},
    year = {2020},
    month = {12},
    issn = {1367-4803},
    doi = {10.1093/bioinformatics/btaa793},
    url = {https://doi.org/10.1093/bioinformatics/btaa793},
    eprint = {https://academic.oup.com/bioinformatics/article-pdf/36/Supplement\_2/i659/35336695/btaa793.pdf},
}
```


### Support or Contact

Having trouble with our tools? Please [contact Jack](mailto:jacklanchantin@gmail.com) and we’ll help you sort it out.
