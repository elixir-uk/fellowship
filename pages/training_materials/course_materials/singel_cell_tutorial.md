---
title: Filter, plot and explore single-cell RNA-seq data
contributors: [Wendi Bacon, Julia Jakiela]
description: A Galaxy Training Tutorial to filter plot and explore single=cell RNA seq data using Scanpy
page_id: single_cell_tutorial
toc: true
training:
  - name: Find this tutorial in TeSS
    registry: TeSS
    url: https://tess.elixir-europe.org/materials/hands-on-for-filter-plot-and-explore-single-cell-rna-seq-data-tutorial
---

<a type="button" class="home-button" href="https://training.galaxyproject.org/training-material/topics/single-cell/tutorials/scrna-case_basic-pipeline/tutorial.html">Go to materials</a>
<br>
<br>

You’ve done all the work to make a single cell matrix, with gene counts and mitochondrial counts and buckets of cell metadata from all your variables of interest. Now it’s time to fully process your data, to remove low quality cells, to reduce the many dimensions of data that make it difficult to work with, and ultimately to try to define clusters and to find biological meaning and insights.

This tutorial works with Scanpy, because currently Galaxy hosts the most Scanpy tools of all of those options.
