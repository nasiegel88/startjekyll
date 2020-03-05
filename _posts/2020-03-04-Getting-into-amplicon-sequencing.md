---
layout: post
title: Getting into amplicon sequencing
---

My lab is getting into the sequencing arena, and my PI has appointed me to spearhead our effort to characterize the infant microbiome during early development.  We are interested in understanding how rapid perturbation of the microbiome influences development with extra emphasis on lung development. I am very excited to delve back into the realm of bioinformatics.

We plan on using Mi-seq to sequence the V3 and V4 regions of the bacterial 16s ribosomal subunit. In short, the subunit allows us to infer what taxa are present in a given sample with high specificity (well not at a strain level) and at a low cost. Since we are a physiology lab, we are not designed to perform DNA isolations from hundreds of samples, so we are working with the sequencing core to get these numerous samples processed in a decent amount of time.

The isolations are familiar to me; however, the preprocessing steps such as adding adaptors and barcodes, are relatively new territory for me. I heard a lot about [qiime2](https://qiime2.org/) and used the software to analyze microbiome data in the past, but it seems too cumbersome for what I plan to do. I will process our fastq files using [dada2](https://benjjneb.github.io/dada2/tutorial.html), a software package that implements much of the fastq processing. The r package also seamlessly hands over the workflow to [phyloseq](https://joey711.github.io/phyloseq/) where data visualization takes place. I am excited to go through some practice samples before I  embark on this next stage of my Ph.D. 