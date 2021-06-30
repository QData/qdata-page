---
categories:
- AIbiomed
title: Bioinformatics - DeepChrome- deep-learning for predicting gene expression from histone modifications
tag:
- EpiGenome
- DeepSequence
- ToolKit
---


## Tool DeepChrome: deep-learning for predicting gene expression from histone modifications

### Paper:  [@Bioinformatics](https://academic.oup.com/bioinformatics/article-abstract/32/17/i639/2450757/DeepChrome-deep-learning-for-predicting-gene)


### [GitHub](https://github.com/QData/DeepChrome)


### [Talk Slides](https://github.com/QData/DeepChrome/blob/master/20160906-ECCB-DeepChrome-RitambharaSingh.pdf)


### Abstract:
Motivation: Histone modifications are among the most important factors that control gene regulation. Computational methods that predict gene expression from histone modification signals are highly desirable for understanding their combinatorial effects in gene regulation. This knowledge can help in developing 'epigenetic drugs' for diseases like cancer. Previous studies for quantifying the relationship between histone modifications and gene expression levels either failed to capture combinatorial effects or relied on multiple methods that separate predictions and combinatorial analysis. This paper develops a unified discriminative framework using a deep convolutional neural network to classify gene expression using histone modification data as input. Our system, called DeepChrome, allows automatic extraction of complex interactions among important features. To simultaneously visualize the combinatorial interactions among histone modifications, we propose a novel optimization-based technique that generates feature pattern maps from the learnt deep model. This provides an intuitive description of underlying epigenetic mechanisms that regulate genes. Results: We show that DeepChrome outperforms state-of-the-art models like Support Vector Machines and Random Forests for gene expression classification task on 56 different cell-types from REMC database. The output of our visualization technique not only validates the previous observations but also allows novel insights about combinatorial interactions among histone modification marks, some of which have recently been observed by experimental studies.



![dp1]({{ site.baseurl }}/pic/dp1.png){:class="img-responsive"}
![dp2]({{ site.baseurl }}/pic/dp2.png){:class="img-responsive"}



### Citations

```
@article{singh2016deepchrome,
  title={DeepChrome: deep-learning for predicting gene expression from histone modifications},
  author={Singh, Ritambhara and Lanchantin, Jack and Robins, Gabriel and Qi, Yanjun},
  journal={Bioinformatics},
  volume={32},
  number={17},
  pages={i639--i648},
  year={2016},
  publisher={Oxford University Press}
}
```


### Support or Contact


Having trouble with our tools? Please [contact Rita](mailto:rs3zz@virginia.edu) and we’ll help you sort it out.
