---
categories:
- AIself
title: CIKM - Document classification with weighted supervised n-gram embedding
tag:
- Represent-ngram 
---

<a name="ask"></a>

### Summary: 
+ Methods and systems for document classification include embedding n-grams from an input text in a latent space, embedding the input text in the latent space based on the embedded n-grams and weighting said n-grams according to spatial evidence of the respective n-grams in the input text, classifying the document along one or more axes, and adjusting weights used to weight the n-grams based on the output of the classifying step.

+ authors: Qi, Yanjun and Bai, Bing 


### Paper1: Sentiment classification with supervised sequence embedding
+ [PDF](https://link.springer.com/content/pdf/10.1007/978-3-642-33460-3_16.pdf)
+ Talk: [Slide](http://www.cs.cmu.edu/~qyj/papersA08/12-talk-ecml2012-qyj.pdf)

+ Abstract
In this paper, we introduce a novel approach for modeling n-grams in a latent space learned from supervised signals. The proposed procedure uses only unigram features to model short phrases (n-grams) in the latent space. The phrases are then combined to form document-level latent representation for a given text, where position of an n-gram in the document is used to compute corresponding combining weight. The resulting two-stage supervised embedding is then coupled with a classifier to form an end-to-end system that we apply to the large-scale sentiment classification task. The proposed model does not require feature selection to retain effective features during pre-processing, and its parameter space grows linearly with size of n-gram. We present comparative evaluations of this method using two large-scale datasets for sentiment classification in online reviews (Amazon and TripAdvisor). The proposed method outperforms standard baselines that rely on bag-of-words representation populated with n-gram features.


### Paper2: Sentiment Classification Based on Supervised Latent n-gram Analysis
+ [PDF](http://www.cs.cmu.edu/~qyj/papersA08/11-cikm.pdf)
+  Talk: [Slide](http://www.cs.cmu.edu/~qyj/papersA08/11-talk-cikm11.pdf)

+ Abstract
In this paper, we propose an efficient embedding for modeling higher-order (n-gram) phrases that projects the n-grams to low-dimensional latent semantic space, where a classification function can be defined. We utilize a deep neural network to build a unified discriminative framework that allows for estimating the parameters of the latent space as well as the classification function with a bias for the target classification task at hand. We apply the framework to large-scale sentimental classification task. We present comparative evaluation of the proposed method on two (large) benchmark data sets for online product reviews. The proposed method achieves superior performance in comparison to the state of the art.



### Citations

```
@misc{qi2014document,
  title={Document classification with weighted supervised n-gram embedding},
  author={Qi, Yanjun and Bai, Bing},
  year={2014},
  month=nov # "~18",
  publisher={Google Patents},
  note={US Patent 8,892,488}
}
```


### Support or Contact

Having trouble with our tools? Please [contact Yanjun Qi](mailto:yq2h@virginia.edu) and we’ll help you sort it out.
