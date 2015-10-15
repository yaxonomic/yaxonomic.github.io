---
layout: page
title: High-level design
permalink: /design/
rel: ..
---
The initial design of our software is a pipeline with a number of distinct modules that will be able to be swapped out and replaced easily. The pipeline wil begin with a preprocessing module that will perform quality filtering, length filters, and collapsing. Another module will map the reads to references in the NCBI database.This module will be wrapped aroud an algorithm implemented by Dr. Fofanov that will handle the alignment of the genetic data. After estimating the composition of the samples, the mapping algorithm will be ran again but on a subset of the original database containing only those references that were mapped to initially.
