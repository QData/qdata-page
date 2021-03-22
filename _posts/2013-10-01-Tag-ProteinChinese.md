---
categories:
- AIbiomed
- AIself
title: Deep Learning for Character-based Information Extraction on Chinese and Protein Sequence
tag:
- Protein
- DeepSequence 
- Semi-SelfLabel
- Represent-ngram
---


### Title: Deep Learning for Character-based Information Extraction on Chinese and Protein Sequence

+ authors: Yanjun Qi, Sujatha Das, Ronan Collobert, Jason Weston


### Paper [ECIR](https://link.springer.com/chapter/10.1007/978-3-319-06028-6_74)
### Supplementary [Here](http://www.cs.cmu.edu/~qyj/zhSenna/moreSenna_supplement.pdf)

### Talk: [Slide](http://www.cs.cmu.edu/~qyj/papersA08/2014_ecir_deep.pdf)


### Abstract
In this paper we introduce a deep neural network architecture to perform information extraction on character-based sequences,
e.g. named-entity recognition on Chinese text or secondary-structure detection on protein sequences. With a task-independent architecture, the
deep network relies only on simple character-based features, which obviates the need for task-specific feature engineering. The proposed discriminative framework includes three important strategies, (1) a deep
learning module mapping characters to vector representations is included
to capture the semantic relationship between characters; (2) abundant
online sequences (unlabeled) are utilized to improve the vector representation through semi-supervised learning; and (3) the constraints of
spatial dependency among output labels are modeled explicitly in the
deep architecture. The experiments on four benchmark datasets have
demonstrated that, the proposed architecture consistently leads to the
state-of-the-art performance.

### Citations

```
@inproceedings{qi2014deep,
  title={Deep learning for character-based information extraction},
  author={Qi, Yanjun and Das, Sujatha G and Collobert, Ronan and Weston, Jason},
  booktitle={European Conference on Information Retrieval},
  pages={668--674},
  year={2014},
  organization={Springer}
}
```


### Support or Contact

Having trouble with our tools? Please [contact Yanjun Qi](mailto:yq2h@virginia.edu) and we’ll help you sort it out.
