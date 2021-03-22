---
categories:
- AIbiomed
title:  GaKCo-SVM- a Fast GApped k-mer string Kernel using COunting
tag:
- fast-gkm-svm
- SeqGenome
- SVM-StringKernel
- Represent-ngram
---

<a name="gakco"></a>
## Tool GaKCo-SVM: a Fast GApped k-mer string Kernel using COunting

### Paper: [@Arxiv](https://arxiv.org/abs/1704.07468) | [@ECML17](https://arxiv.org/abs/1704.07468)

### [GitHub](https://github.com/QData/GaKCo-SVM)

### [Talk PDF](https://github.com/QData/GaKCo-SVM/blob/master/GaKCo-ECML17-Slides.pdf)

### [Poster](https://github.com/QData/GaKCo-SVM/blob/master/2017WiML%20GaKCo.pptx.pdf)

### Abstract:
String Kernel (SK) techniques, especially those using gapped k-mers as features (gk), have obtained great success in classifying sequences like DNA, protein, and text. However, the state-of-the-art gk-SK runs extremely slow when we increase the dictionary size (Σ) or allow more mismatches (M). This is because current gk-SK uses a trie-based algorithm to calculate co-occurrence of mismatched substrings resulting in a time cost proportional to O(ΣM). We propose a \textbf{fast} algorithm for calculating \underline{Ga}pped k-mer \underline{K}ernel using \underline{Co}unting (GaKCo). GaKCo uses associative arrays to calculate the co-occurrence of substrings using cumulative counting. This algorithm is fast, scalable to larger Σ and M, and naturally parallelizable. We provide a rigorous asymptotic analysis that compares GaKCo with the state-of-the-art gk-SK. Theoretically, the time cost of GaKCo is independent of the ΣM term that slows down the trie-based approach. Experimentally, we observe that GaKCo achieves the same accuracy as the state-of-the-art and outperforms its speed by factors of 2, 100, and 4, on classifying sequences of DNA (5 datasets), protein (12 datasets), and character-based English text (2 datasets), respectively.

![gakco]({{ site.baseurl }}/pic/gakco.png){:class="img-responsive"}



### Citations

```
@inproceedings{singh_gakco:_2017,
	location = {Cham},
	title = {GaKCo: A Fast Gapped k-mer String Kernel Using Counting},
	isbn = {978-3-319-71249-9},
	pages = {356--373},
	booktitle = {Machine Learning and Knowledge Discovery in Databases},
	publisher = {Springer International Publishing},
	author = {Singh, Ritambhara and Sekhon, Arshdeep and Kowsari, Kamran and Lanchantin, Jack and Wang, Beilun and Qi, Yanjun},
	editor = {Ceci, Michelangelo and Hollmén, Jaakko and Todorovski, Ljupčo and Vens, Celine and Džeroski, Sašo},
	date = {2017}
}
```


### Support or Contact

Having trouble with our tools? Please [contact Rita](mailto:rs3zz@virginia.edu) and we’ll help you sort it out.
