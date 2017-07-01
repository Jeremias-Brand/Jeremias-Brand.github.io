---
layout: page
title: Phylogeny
---

## Phylogenetic dependence ##

Since I am studying the evolution of sexual traits, it is crucial to have a good estimate of the phylogeny. This is because the morphology different species is not statistically independent but dependent through a common evolutionary history. We would for example assume that closely related species also tend to look similar. If we want to test for correlations between traits we need to take this dependence into account and we can do that by correcting our test for phylogeny. 

## RNAseq ##

We are inferring phylogenies using RNA sequencing. In this method we extract the entirety of RNA present in a whole animal and sequence it using next generation sequencing. This then gives us access to all the genes that are currently being transcribed in this specimen. After sequencing the RNA needs to be put together into transcriptomes - that is the set of all expressed transcripts. I am currently working on a bioinformatics pipeline to do this. Here is a drawing of the pipeline when it is given two batches of sequences.

![alt text](https://jeremias-brand.github.io/img/macpipe_trans_concept.png "directed acyclic graph of the transcriptome assembly pipeline")
