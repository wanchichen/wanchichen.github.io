---
title: "In Silico Model for miRNA-mediated Regulatory Network in Cancer"
collection: publications
permalink: /publication/miRNA
excerpt: "Current data analyses on gene expression are mostly focused on differential gene/transcript expression in big data-driven studies. However, a poor connection to the proteome changes is a widespread problem in current data analyses. In this study, we overcome these limitations and introduce a graph-based learning model, PTNet, which simulates the miRNAs (microRNAs) that regulate gene expression post-transcriptionally in silico."
date: 2021-07-01
venue: "Briefings in Bioinformatics"
paperurl: "https://academic.oup.com/bib/advance-article-abstract/doi/10.1093/bib/bbab264/6323206?redirectedFrom=fulltext"
authors: "Khandakar Tanvir Ahmed, Jiao Sun, William Chen, Irene Martinez, Sze Cheng, Wencai Zhang, Jeongsik Yong, and Wei Zhang."
citation: "Khandakar Tanvir Ahmed, Jiao Sun, William Chen, Irene Martinez, Sze Cheng, Wencai Zhang, Jeongsik Yong, and Wei Zhang. (2021) &quot;In Silico Model for miRNA-mediated Regulatory Network in Cancer.&quot; <i>Briefings in Bioinformatics</i>."
---

Abstract: Deregulation of gene expression is associated with the pathogenesis of numerous human diseases including cancer. Current data analyses on gene expression are mostly focused on differential gene/transcript expression in big data-driven studies. However, a poor connection to the proteome changes is a widespread problem in current data analyses. This is partly due to the complexity of gene regulatory pathways at the post-transcriptional level. In this study, we overcome these limitations and introduce a graph-based learning model, PTNet, which simulates the miRNAs (microRNAs) that regulate gene expression post-transcriptionally in silico. Our model does not require large-scale proteomics studies to measure the protein expression and can successfully predict the protein levels by considering the miRNA-mRNA interaction network, the mRNA expression, and the miRNA expression. Large-scale experiments on simulations and real cancer high-throughput datasets using PTNet validated that (1) the miRNA-mediated interaction network affects the abundance of corresponding proteins; (2) the predicted protein expression has a higher correlation with the proteomics data (groundtruth) than the mRNA expression data. The classification performance also shows that the predicted protein expression has an improved prediction power on cancer outcomes compared to the prediction done by the mRNA expression data only or considering both mRNA and miRNA.

Download [here](https://academic.oup.com/bib/advance-article-abstract/doi/10.1093/bib/bbab264/6323206?redirectedFrom=fulltext)

Code available [here](https://github.com/CompbioLabUCF/PTNet)
