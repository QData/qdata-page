---
categories:
- AItrust
title: Blackbox Generation of Adversarial Text Sequences 
tag:
- 1-Evasion
- 4-VisualizeBench
- textattack
- Generate-Text 
---

<a name="wordbug"></a>

### Title: Black-box Generation of Adversarial Text Sequences to Fool Deep Learning Classifiers

![evadePDF]({{ site.baseurl }}pic/wordbug.png){:class="img-responsive"}


### GitHub: [https://github.com/QData/deepWordBug](https://github.com/QData/deepWordBug)

### TalkSlide: [URL]({{ site.baseurl }}pic/2018_Ji_DLS_presentation.pdf)

### Paper [Arxiv](https://arxiv.org/abs/1801.04354)
 Published @ 2018 IEEE Security and Privacy Workshops (SPW), 
co-located with the 39th IEEE Symposium on Security and Privacy. 

+ Extended version @ [PDF](https://github.com/QData/deepWordBug/blob/master/about/Ji2017_EvadeNLP-extended.pdf)


### Abstract
Although various techniques have been proposed to generate adversarial samples for white-box attacks on text, little attention has been paid to a black-box attack, which is a more realistic scenario. In this paper, we present a novel algorithm, DeepWordBug, to effectively generate small text perturbations in a black-box setting that forces a deep-learning classifier to misclassify a text input. We develop novel scoring strategies to find the most important words to modify such that the deep classifier makes a wrong prediction. Simple character-level transformations are applied to the highest-ranked words in order to minimize the edit distance of the perturbation. We evaluated DeepWordBug on two real-world text datasets: Enron spam emails and IMDB movie reviews. Our experimental results indicate that DeepWordBug can reduce the classification accuracy from 99% to around 40% on Enron data and from 87% to about 26% on IMDB. Also, our experimental results strongly demonstrate that the generated adversarial sequences from a deep-learning model can similarly evade other deep models. 

#### We build an interactive extension to visualize DeepWordbug:  

- Interactive Live Demo @  [ULR](http://adv-text-flask-env.cygeeu97fg.us-east-1.elasticbeanstalk.com/dwb)

![evadePDF]({{ site.baseurl }}pic/demo.png){:class="img-responsive"}



### Citations

```
@INPROCEEDINGS{JiDeepWordBug18, 
author={J. Gao and J. Lanchantin and M. L. Soffa and Y. Qi}, 
booktitle={2018 IEEE Security and Privacy Workshops (SPW)}, 
title={Black-Box Generation of Adversarial Text Sequences to Evade Deep Learning Classifiers}, 
year={2018}, 
pages={50-56}, 
keywords={learning (artificial intelligence);pattern classification;program debugging;text analysis;deep learning classifiers;character-level transformations;IMDB movie reviews;Enron spam emails;real-world text datasets;scoring strategies;text input;text perturbations;DeepWordBug;black-box attack;adversarial text sequences;black-box generation;Perturbation methods;Machine learning;Task analysis;Recurrent neural networks;Prediction algorithms;Sentiment analysis;adversarial samples;black box attack;text classification;misclassification;word embedding;deep learning}, 
doi={10.1109/SPW.2018.00016}, 
month={May},}
```


### Support or Contact


Having trouble with our tools? Please [contact me](mailto:yq2h@virginia.edu) and we’ll help you sort it out.
