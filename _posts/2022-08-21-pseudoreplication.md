---
layout: post
title: Pseudoreplication
---

**Pseudoreplication** means that you mistakenly treat experimental samples as independent. I commonly see this error in publications. Here is how to spot and avoid it:

The sample size (N) is the number of independent observations and fundamentally affects any statistical hypothesis test. Pseudoreplication erroneously increases the sample size by counting dependent samples as independent. The most common pseudoreplication error is counting technical replicates towards sample size. For example, repeated measurements of metabolic activity of a single bacterial culture 🧫 are not independent. Only separate dishes 🧫🧫 that have grown independently are!

We can see this with a silly example: 
Measuring the height of three giraffes three times :
3x🦒 + 3x🦒 + 3x🦒 
is not the same as measuring the height of nine once.
🦒 + 🦒 + 🦒 + 🦒 + 🦒 + 🦒 + 🦒 + 🦒 + 🦒

You get a more accurate estimate per giraffe with technical replicates, but you have not increased your sample size.
If you apply a statistical test across all your technical replicates, you artificially increase the sample size leading to overconfidence and too low p-values. Nevertheless, it occurs commonly in the scientific literature.

## Avoid pseudoreplication by asking ## 

> What is my experimental unit?

Then measure as many independent observations of the experimental unit. 
It sounds simple, but it is easy to make a mistake.
If you care about the effect of polluted water on fish 🐠, then you need to replicate the water treatment, not just put more fish in the same tank. 
The additional fish are pseudoreplicates! See a detailed explanation [here](https://online.stat.psu.edu/stat502_fa21/lesson/7/7.1)

If you want to learn more about pseudoreplication, I highly recommend [this paper](https://journals.plos.org/plosbiology/article?id=10.1371/journal.pbio.2005282) on what sample size is.

This was originally a [tweet](https://twitter.com/Jere_Brand/status/1560706273724743680?s=20&t=1jjKzbqqIYUVcd-_z65Zrw).
