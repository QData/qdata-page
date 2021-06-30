---
categories:
- AIbiomed
- AIself
title: MLCB - Prototype Matching Networks for Large-Scale Multi-label Genomic Sequence Classification
tag:
- SeqGenome
- DeepSequence
- Rank-Metric
---

<a name="pmn"></a>

## Prototype Matching Networks : A novel deep learning architecture for Large-Scale Multi-label Genomic Sequence Classification


### Paper: [@Arxiv](https://arxiv.org/abs/1710.11238)


### Abstract
One of the fundamental tasks in understanding genomics is the problem of predicting Transcription Factor Binding Sites (TFBSs). With more than hundreds of Transcription Factors (TFs) as labels, genomic-sequence based TFBS prediction is a challenging multi-label classification task. There are two major biological mechanisms for TF binding: (1) sequence-specific binding patterns on genomes known as "motifs" and (2) interactions among TFs known as co-binding effects. In this paper, we propose a novel deep architecture, the Prototype Matching Network (PMN) to mimic the TF binding mechanisms. Our PMN model automatically extracts prototypes ("motif"-like features) for each TF through a novel prototype-matching loss. Borrowing ideas from few-shot matching models, we use the notion of support set of prototypes and an LSTM to learn how TFs interact and bind to genomic sequences. On a reference TFBS dataset with 2.1 million genomic sequences, PMN significantly outperforms baselines and validates our design choices empirically. To our knowledge, this is the first deep learning architecture that introduces prototype learning and considers TF-TF interactions for large-scale TFBS prediction. Not only is the proposed architecture accurate, but it also models the underlying biology.



### Citations

```
@article{lanchantin2017prototype,
  title={Prototype Matching Networks for Large-Scale Multi-label Genomic Sequence Classification},
  author={Lanchantin, Jack and Sekhon, Arshdeep and Singh, Ritambhara and Qi, Yanjun},
  journal={arXiv preprint arXiv:1710.11238},
  year={2017}
}
```

### Support or Contact

Having trouble with our tools? Please [contact Jack](mailto:jacklanchantin@gmail.com) and we’ll help you sort it out.
