# DeepLearning_Project
Active Domain Adaptation using SDM

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



#Acknowledgement
Our code is based on https://github.com/TencentYoutuResearch/ActiveLearning-SDM
