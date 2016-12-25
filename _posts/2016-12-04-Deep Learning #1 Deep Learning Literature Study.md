---
layout: post
title: Deep Learning in Genomics
---

## Deep Learning for Predicting Sequence Specificities of DNA/RNA Binding Proteins ##
## Genomic Big Data Analysis ##

The paper I want to review is named Predicting the Sequence Specificities of DNA- and RNA-binding Proteins by Deep Learning published on Nature Biotechnology 2015. I am personally interested in this article, because of two reasons. First, I recently worked with synthetic biologists to optimize the quantity of transcription factors, which belongs to DNA-binding proteins, and it helps me develop better understanding by studying the most advanced research about it. Second, I am curious about how to apply deep learning in DNA/RNA sequences in general, the advantages and obstacles. 
###Why deep learning? ###
As a matter of fact, researchers has been exploring different methods for predicting sequence specificities of DNA/RNA binding proteins, such as MatrixREDUCE, MEMERIS, Covariance models, and RNAcontext, etc. Then what we can gain from this deep learning method? I summarize the following reasons:
* 	It outperforms all the aforementioned methods with both in vivo and in vitro datasets in predicting DNA- and RNA- binding protein specificities. 
* 	Ease of training across different measurement platforms, such as Protein-DNA Binding Microarray (PBM), Chromatin Immunoprecipitation (ChIP) Assays, and HT-SELEX. 
* 	Parameter tuning is automatic, more generic and less labor intensive for new datasets.
How is Sequence Specificities Measured?
Before taking a look into the model, one need to get a basic idea about how those input datasets are generated. 9-13

![alt text](https://rawgit.com/jinzhenfan/jinzhenfan.github.io/master/images/antibiotics/antibiotics.jpg "How much antibiotics is in your salmon?")