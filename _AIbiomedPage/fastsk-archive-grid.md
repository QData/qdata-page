---
layout: tag
permalink: /tags/fastsk/
taxonomy: fast-gkm-svm
title: fast-gkm-svm
description: 'A suite of tools we designed for making gkm-svm algorithm faster which achieving the same prediction as gkm-svm-latest. ' 
entries_layout: grid
---


<div>
    This page summarizes our efforts for re-implementing gkm-svm algorithm with a novel and faster algorithmic design and better programming structure. Please feel free to email me when you find my typos. 
</div>
<br>
<hr>


## overview of fast-gkm-svm

Existing gkm-SVM algorithms 
		 suffer from the slow kernel computation time, as they depend 
		 exponentially on the sub-sequence feature-length, number of mismatch 
		 positions, and the task's alphabet size. 
		 In this project, we introduce a fast and scalable algorithm for 
		 calculating gapped k-mer string kernels. Our method, named FastSK,
		  uses a simplified kernel formulation that decomposes the kernel 
		  calculation into a set of independent counting operations over the 
		  possible mismatch positions. This simplified decomposition allows us 
		  to devise a fast Monte Carlo approximation that rapidly converges. 
		  FastSK can scale to much greater feature lengths, allows us to 
		  consider more mismatches, and is performant on a variety of sequence
		   analysis tasks.



+ Paper [Bioinformatics](https://academic.oup.com/bioinformatics/article/36/Supplement_2/i857/6055916)


+ Documentation [@readthedoc](https://fastsk.readthedocs.io/en/master/)

## Important wrappers we develop to help users 

#### python wrapper 


+ GitHub: [https://github.com/QData/FastSK](https://github.com/QData/FastSK)


#### R wrapper 
+ (to come)


## Contact
Have questions or suggestions? Feel free to [ask me on Twitter](https://twitter.com/Qdatalab) or [email me](https://qiyanjun.github.io/Homepage/).

Thanks for reading!
