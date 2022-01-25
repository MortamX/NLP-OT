# NLP-OT

This repository contains the work done during a research project with Paul Mortamet and guided by Dr. François Yvon.

The Notebook contains the final report and the code that we used to get our results and the changes that we tested.

## Abstract

There are few precise studies on the use of Optimal Transport in word alignment problems between sentences of different languages (Word Alignment). Our study follows on from the work of Zi-Yi Dou and Graham Neubig, who introduced this method slightly into word alignment problems. We have studied the implications of the Sinkhorn algorithm and the construction of the cost matrix in the approximation of the Optimal Transport Plan. By observing the different successive steps of the Dou and Neubig method, we propose an optimisation of the Sinkhron algorithm through a study on the entropy regularisation parameter. Then, we propose a modification of the construction of the cost matrix, by defining two new distances. We conclude our study by proposing a new method of alignment extraction, more flexible and adapted to the different distributions.

## Content

- Introduction
    - Embedding spaces
    - Multilingual embedding spaces
    - Earth mover's distance
- Word Alignment
- Optimal transport
- Our research
    - Entropic regularization
    - A deeper analysis of the cost matrix
- Conclusion