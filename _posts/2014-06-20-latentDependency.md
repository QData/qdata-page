---
categories:
- AIself
title: NeurIPS- Learning the Dependency Structure of Latent Factors
tag:
- Learn-Dictionary
- Graph-generative
---


<a name="sc"></a>

### Paper: [@NeurIPS12](https://papers.nips.cc/paper/4636-learning-the-dependency-structure-of-latent-factors) 
+ Yunlong He, Yanjun Qi, Koray Kavukcuoglu, Haesun Park


### [GitHub](https://github.com/DeepLearning4BioSeqText/Paper12-NIPS-SparseGGM4LatentFactors)

### [Poster PDF](https://www.cs.virginia.edu/yanjun/paperA14/2012_SLFA_NIPS.pdf)



### Abstract:
In this paper, we study latent factor models with the dependency structure in the latent space. We propose a general learning framework which induces sparsity on the undirected graphical model imposed on the vector of latent factors. A novel latent factor model SLFA is then proposed as a matrix factorization problem with a special regularization term that encourages collaborative reconstruction. The main benefit (novelty) of the model is that we can simultaneously learn the lower-dimensional representation for data and model the pairwise relationships between latent factors explicitly. An on-line learning algorithm is devised to make the model feasible for large-scale learning problems. Experimental results on two synthetic data and two real-world data sets demonstrate that pairwise relationships and latent factors learned by our model provide a more structured way of exploring high-dimensional data, and the learned representations achieve the state-of-the-art classification performance.


![slf]({{ site.baseurl }}/pic/slf1.png){:class="img-responsive"}

![slf]({{ site.baseurl }}/pic/slf2.png){:class="img-responsive"}

![slf]({{ site.baseurl }}/pic/slf3.png){:class="img-responsive"}

### Citations

```
@inproceedings{he2012learning,
  title={Learning the dependency structure of latent factors},
  author={He, Yunlong and Qi, Yanjun and Kavukcuoglu, Koray and Park, Haesun},
  booktitle={Advances in neural information processing systems},
  pages={2366--2374},
  year={2012}
}
```


### Support or Contact

Having trouble with our tools? Please [contact Yanjun Qi](mailto:yq2h@virginia.edu) and we’ll help you sort it out.
