---
title: "Calculating Edit Distance for Large Sets of String Pairs using MapReduce"
date: 2014-07-10
research_type: 
- peer-reviewed-article
links:
- name: Preprint
  url: jhaver-2014-edit-distance.pdf
  icon: far fa-file-pdf
  local: true  
citation: >-
  **Shagun Jhaver**, [Latifur Khan](https://personal.utdallas.edu/~lkhan/), and [Bhavani Thuraisingham](https://personal.utdallas.edu/~bhavani.thuraisingham/) (2014), “Calculating Edit Distance for Large Sets of String Pairs using MapReduce,” *In Proceedings of the ASE International Conference on Big Data*. 
haiku: >-
  Levenshtein distance / Dynamic programming / MapReduce.
---

## Important links

- [Paper (preprint)](jhaver-2014-edit-distance.pdf)

## Abstract

Given two strings X and Y over a finite alphabet, the edit distance between X and Y , d(X, Y) is the number of elementary edit operations required to edit X into Y . A dynamic programming algorithm elegantly computes this distance. In this paper, we investigate the parallelization of calculating edit distance for a large set of strings using MapReduce, a popular parallel computing framework. We propose SIM MR and PRE MR algorithms, parallel versions of the dynamic program- ming solution, and present implementations of these algorithms. We study different cases by varying algorithm parameters, input size and number of parallel nodes, and analytically and experimentally confirm the superiority of our methods over the usual dynamic programming approach. This study demonstrates how MapReduce parallelization opens new avenues of designing for dynamic programming algorithms.

## BibTeX citation

```bibtex
@inproceedings{jhaver:2014Edit,
	title={Calculating edit distance for large sets of string pairs using MapReduce},
  author={Jhaver, Shagun and Khan, Latifur and Thuraisingham, Bhavani},
  year={2014},
  publisher={Academy of Science and Engineering (ASE), USA,{\copyright} ASE 2014}
}
```
