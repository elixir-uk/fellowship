---
layout: post
title: GTN tutorial. Filter, plot and explore single-cell RNA-seq data
description: A Galaxy Training Tutorial to filter plot and explore single-cell RNA seq data using Scanpy
date: 2023-09-11
author: [j-jakiela, w-bacon]
image: /images/gtn-tutorial.jpg
tag: [Courses, Sequencing data, Single-cell data]
featured: true
go_to: https://gxy.io/GTN:T00247
link_tag: GTN tutorial
---

You’ve done all the work to make a single cell matrix, with gene counts and mitochondrial counts and buckets of cell metadata from all your variables of interest. Now it’s time to fully process your data, to remove low quality cells, to reduce the many dimensions of data that make it difficult to work with, and ultimately to try to define clusters and to find biological meaning and insights.

This tutorial works with Scanpy, because currently Galaxy hosts the most Scanpy tools of all of those options.