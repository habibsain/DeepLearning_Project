# DeepLearning_Project
### Active Domain Adaptation using SDM

In this report we analyse and implement the method proposed by
the authors of the original research paper and try to improve it based on our limited understanding of the field. 

There are several approaches towards
Domain Adaptation and active learning is one popular method. Despite there being several ac-
tive domain adaptation (ADA) methods, they are mostly vulnerable to overfitting, and needs
specific query functions. But The new
method called Select by Distinctive Margin (SDM) avoids the problem of overfitting
by selecting hard examples from the source domain in order to find transferable data which is
used for domain adaptation. We have implemented the code on different datasets and tweaked
the code in order to get some improvements. Changes in Optimizers, Loss functions and batch
normalization layer were some of our approach to try and improve this paper.

# Report

Original paper: [arXiv](https://arxiv.org/abs/2203.05738).

Our report is [Here](https://www.researchgate.net/publication/374535841_Active_Domain_Adaptation_using_Selective_Distinctive_Margin?utm_source=twitter&rgutm_meta1=eHNsLTc2OVdETzFOWlNxeTZpNVJJRkVmRk1ZREROdGpIcGNOQWFkcmZCeDIvak81cnBqYi9VSkhiUEhaYVRUaXp4bVpzeWw2Q1VjTVJ6T2VYRFpQMk1RdDk3bz0%3D)


# Acknowledgement
Our code is based on [SDM](https://github.com/TencentYoutuResearch/ActiveLearning-SDM)
