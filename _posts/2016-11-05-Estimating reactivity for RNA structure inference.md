---
layout: post
title: Comparison of two RNA structure models based on SHAPE-Seq data 
category: analysis
---

Due to the complexity of genomic datasets, the best approach to analyze data is often not clear from the beginning. In fact, several approaches and tools exist for analysis of most genomic datasets. Each approach is optimized and validated for specific datasets and may not be applicable across the board. However, due to lack of clear guidelines on when to use or not use an approach, data analysis teams sometimes end up taking suboptimal or even inapplicable approaches. This can lead to contradictory results between different studies on the same subjects. Such contradictions have to be resolved by careful examination of considerations/assumptions that may have motivated an approach.

In this article, we utilized SHAPE-Seq data sets from a Nature Letter publication$^1$, and compare the reactivity profiles obtained using the formula derived by Aviran et al., 2011 and another formula used by Ding et al., 2014. The maximum likelihood result obtained by Aviran et al can be found in the reference$^2$. Necessary details of Ding et al.'s research are given here but you are also encouraged to read the paper.$^1$

For any structure-profiling experiment, as described by Aviran et al., read mapping results can be tallied and summarized as stop counts for each nucleotide. Consider a transcript of length $n$. Let us label the nucleotides with indices 1 through $n$ with 1 being the 3' end. For this transcript, there will be $n+1$ count summaries for each of the experiment and control channel, also called as (+) channel and (-) channel, respectively. These counts can be denoted as 

 