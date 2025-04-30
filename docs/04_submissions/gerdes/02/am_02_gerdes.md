---
layout: default
title: Session 01
nav_exclude: true
---

### Task 02.01 - Question Selection

## 01 - focus on model

### tripod

**Round I**

1. I am examining the application of supervised learning for predicting semantic coordinates from textual data
2. because I want to find out how effectively a custom-trained predictive model can map textual content to semantically meaningful spatial coordinates
3. in order to determine the advantages and disadvantages such an approach offers over a combination of high-dimensional text embeddings with traditional dimensionality reduction techniques.

**Round II**

- goal
  - The goal of this module paper is to develop and evaluate a supervised learning approach for predicting semantic spatial coordinates from text, comparing its performance against established dimensionality reduction pipelines.

- preliminary research question
  - How does a custom-trained supervised learning model for predicting semantic coordinates from text compare to hybrid approaches using BERT embeddings with UMAP reduction in terms of startup time, inference speed, accuracy, and file size?

- hypothesis
  - I hypothesize that a supervised learning model trained directly on mapping text to semantic coordinates will demonstrate faster inference times and smaller file sizes than hybrid BERT+UMAP approaches, while maintaining acceptable accuracy in preserving semantic relationships.

### considerations

- broader approach indirectly incorporating the dataset generation as a resulting sub-question
- allows to focus on the model training and performance evaluation
- makes the paper results dependant on the (possibly very heavy) technical implementation for ml-one
- addresses possible gap in literature (knowledge gap criteria)

## 02 - focus on dataset

### tripod

**Round I**

1. I am examining methods for generating mid-scale datasets that map a large range of factual text to semantically coherent spatial coordinates
2. because I want to understand how different dimensionality reduction techniques create spatial structures that preserve semantic relationships in textual data and how these approaches differ
3. in order to determine an effective approach for creating a training dataset that enable semantic coordinate prediction through supervised learning

**Round II**

- goal
  - The goal of this module paper is to discover sources for text data and use them to develop and evaluate a pipeline for generating mid-scale datasets that map textual content to semantically meaningful spatial coordinates.


- preliminary research question
  - How can dimensionality reduction techniques like PCA, t-SNE, and UMAP be optimally configured and used to generate a training dataset that maps encyclopedic (factual) texts to semantically coherent spatial coordinates?

- hypothesis
  - I hypothesize that combining text embeddings and dimensionality reduction techniques will yield a spatial-semantically sound structure within the dataset, useful for training in predictive modeling.

### considerations

- smaller scope (possibly too small on the technical implementation (ml-one) part)
- more existing literature available (everything analyzing spatial structure in text data)
- knowledge gap in terms of aggregating a text coordinate dataset alone is much less relevant
- hypothesis needs work