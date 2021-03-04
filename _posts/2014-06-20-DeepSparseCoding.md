---
categories:
- AIself
title:  Unsupervised Feature Learning by Deep Sparse Coding
tag:
- Learn-Dictionary
---


<a name="sc"></a>

### Paper: [@Arxiv](https://arxiv.org/pdf/1312.5783) 
+ Y He, K Kavukcuoglu, Y Wang, A Szlam, Y Qi



### [Talk PDF](http://www.cs.virginia.edu/yanjun/paperA14/2014-sdm-deepsc-talk.pdf)


### Abstract:
In this paper, we propose a new unsupervised feature learning framework, namely Deep Sparse Coding (DeepSC), that extends sparse coding to a multi-layer architecture for visual object recognition tasks. The main innovation of the framework is that it connects the sparse-encoders from different layers by a sparse-to-dense module. The sparse-to-dense module is a composition of a local spatial pooling step and a low-dimensional embedding process, which takes advantage of the spatial smoothness information in the image. As a result, the new method is able to learn several levels of sparse representation of the image which capture features at a variety of abstraction levels and simultaneously preserve the spatial smoothness between the neighboring image patches. Combining the feature representations from multiple layers, DeepSC achieves the state-of-the-art performance on multiple object recognition tasks.


![gakco]({{ site.baseurl }}/pic/dsc.png){:class="img-responsive"}



### Citations

```
@misc{he2013unsupervised,
    title={Unsupervised Feature Learning by Deep Sparse Coding},
    author={Yunlong He and Koray Kavukcuoglu and Yun Wang and Arthur Szlam and Yanjun Qi},
    year={2013},
    eprint={1312.5783},
    archivePrefix={arXiv},
    primaryClass={cs.LG}
}
```


### Support or Contact

Having trouble with our tools? Please [contact Yanjun Qi](mailto:yq2h@virginia.edu) and we’ll help you sort it out.
