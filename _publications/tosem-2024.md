---
title: "KADEL: Knowledge-Aware Denoising Learning for Commit Message Generation"
collection: publications
permalink: /publication/tosem-2024
excerpt: 'Commit messages are natural language descriptions of code changes, which are important for software evolution such as code understanding and maintenance. 
However, previous methods are trained on the entire dataset without considering the fact that a portion of commit messages adhere to good practice (i.e., good-practice commits), while the rest do not.
On the basis of our empirical study, we discover that training on good-practice commits significantly contributes to the commit message generation.
Motivated by this finding, we propose a novel knowledge-aware denoising learning method called KADEL. 
Considering that good-practice commits constitute only a small proportion of the dataset, we align the remaining training samples with these good-practice commits.
To achieve this, we propose a model that learns the commit knowledge by training on good-practice commits. 
This knowledge model enables supplementing more information for training samples that do not conform to good practice.
However, since the supplementary information may contain noise or prediction errors, we propose a dynamic denoising training method. This method composes a distribution-aware confidence function and a dynamic distribution list, which enhances the effectiveness of the training process.
Experimental results on the whole MCMD dataset demonstrate that our method overall achieves state-of-the-art performance compared with previous methods. 
Our source code and data are available 
at [https://github.com/DeepSoftwareAnalytics/KADEL](https://github.com/DeepSoftwareAnalytics/KADEL)'
date: 2024-1-16
---

## Abstract

Commit messages are natural language descriptions of code changes, which are important for software evolution such as code understanding and maintenance. 
However, previous methods are trained on the entire dataset without considering the fact that a portion of commit messages adhere to good practice (i.e., good-practice commits), while the rest do not. 

On the basis of our empirical study, we discover that training on good-practice commits significantly contributes to the commit message generation. 

Motivated by this finding, we propose a novel knowledge-aware denoising learning method called KADEL. 
Considering that good-practice commits constitute only a small proportion of the dataset, we align the remaining training samples with these good-practice commits. 
To achieve this, we propose a model that learns the commit knowledge by training on good-practice commits. 
This knowledge model enables supplementing more information for training samples that do not conform to good practice. However, since the supplementary information may contain noise or prediction errors, we propose a dynamic denoising training method. 
This method composes a distribution-aware confidence function and a dynamic distribution list, which enhances the effectiveness of the training process. 

Experimental results on the whole MCMD dataset demonstrate that our method overall achieves state-of-the-art performance compared with previous methods.

Our source code and data are available 
at [https://github.com/DeepSoftwareAnalytics/KADEL](https://github.com/DeepSoftwareAnalytics/KADEL)

## Links

- [View at ACM](https://dl.acm.org/doi/10.1145/3643675)

- [View at Arxiv](https://arxiv.org/abs/2401.08376)

- [Related Dataset: **M**ulti-language **C**ommit **M**essage **D**ataset, MCMD](https://doi.org/10.5281/zenodo.5025758)

- [Code](https://github.com/DeepSoftwareAnalytics/KADEL)

## Related Works

[A large-scale empirical study of commit message generation: models, datasets and evaluation](./emse-2022)

[On the Evaluation of Commit Message Generation Models: An Experimental Study](./icsme-2021)


## Recommended citation

### BibTex

```bibtex
@article{KADEL_CMG_24,
author = {Tao, Wei and Zhou, Yucheng and Wang, Yanlin and Zhang, Hongyu and Wang, Haofen and Zhang, Wenqiang},
title = {KADEL: Knowledge-Aware Denoising Learning for Commit Message Generation},
year = {2024},
issue_date = {June 2024},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
volume = {33},
number = {5},
issn = {1049-331X},
url = {https://doi.org/10.1145/3643675},
doi = {10.1145/3643675},
journal = {ACM Trans. Softw. Eng. Methodol.},
month = {jun},
articleno = {133},
numpages = {32}
}
```
