---
categories:
- AIbiomed
title: Bioinformatics - DeepDiff- Deep-learning for predicting Differential gene expression from histone modifications
tag:
- EpiGenome
- DeepSequence
---

## Tool DeepDIff: DeepDiff: Deep-learning for predicting Differential gene expression from histone modifications

### Paper:  
+ [@Arxiv version](https://arxiv.org/abs/1807.03878) 
+ Published at [Bioinformatics](https://academic.oup.com/bioinformatics/article/34/17/i891/5093224?rss=1)

### [GitHub](https://github.com/QData/DeepDiffChrome)

### [talk slides PDF](https://github.com/QData/DeepDiffChrome/blob/master/ArshDeepDiffTalk.pdf)


### Abstract:
Computational methods that predict differential gene expression from histone modification signals are highly desirable for understanding how histone modifications control the functional heterogeneity of cells through influencing differential gene regulation. Recent studies either failed to capture combinatorial effects on differential prediction or primarily only focused on cell type-specific analysis. In this paper, we develop a novel attention-based deep learning architecture, DeepDiff, that provides a unified and end-to-end solution to model and to interpret how dependencies among histone modifications control the differential patterns of gene regulation. DeepDiff uses a hierarchy of multiple Long short-term memory (LSTM) modules to encode the spatial structure of input signals and to model how various histone modifications cooperate automatically. We introduce and train two levels of attention jointly with the target prediction, enabling DeepDiff to attend differentially to relevant modifications and to locate important genome positions for each modification. Additionally, DeepDiff introduces a novel deep-learning based multi-task formulation to use the cell-type-specific gene expression predictions as auxiliary tasks, encouraging richer feature embeddings in our primary task of differential expression prediction. Using data from Roadmap Epigenomics Project (REMC) for ten different pairs of cell types, we show that DeepDiff significantly outperforms the state-of-the-art baselines for differential gene expression prediction. The learned attention weights are validated by observations from previous studies about how epigenetic mechanisms connect to differential gene expression. Codes and results are available at [deepchrome.net](deepchrome.net)

![DeepDiffChrome]({{ site.baseurl }}/pic/diff0.png){:class="img-responsive"}


![DeepDiffChrome]({{ site.baseurl }}/pic/diff1.png){:class="img-responsive"}

![DeepDiffChrome]({{ site.baseurl }}/pic/diff2.png){:class="img-responsive"}

![DeepDiffChrome]({{ site.baseurl }}/pic/diff3.png){:class="img-responsive"}

### Citations

```
@article{ArDeepDiff18,
author = {Sekhon, Arshdeep and Singh, Ritambhara and Qi, Yanjun},
title = {DeepDiff: DEEP-learning for predicting DIFFerential gene expression from histone modifications},
journal = {Bioinformatics},
volume = {34},
number = {17},
pages = {i891-i900},
year = {2018},
doi = {10.1093/bioinformatics/bty612},
URL = {http://dx.doi.org/10.1093/bioinformatics/bty612},
eprint = {/oup/backfile/content_public/journal/bioinformatics/34/17/10.1093_bioinformatics_bty612/2/bty612.pdf}
}
```


### Support or Contact

Having trouble with our tools? Please [contact Arsh](mailto:as5cu@virginia.edu) and we’ll help you sort it out.
