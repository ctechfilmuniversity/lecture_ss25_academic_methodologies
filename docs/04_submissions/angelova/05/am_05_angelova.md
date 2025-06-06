---
layout: default
title: Homework
nav_exclude: true
---

**Academic Methodologies**
  
Prof. Dr. Lena Gieseke \| l.gieseke@filmuniversitaet.de \| Film University Babelsberg KONRAD WOLF \
Alexander Walmsley \| a.walmsley@filmuniversitaet.de \| Film University Babelsberg KONRAD WOLF


## Session 05 - Qualitative Research

* [Your Paper](#your-paper)
    * [Task 05.01 - Related Work](#task-0501---related-work)

## Your Paper

### Task 05.01 - Related Work

Collect related work for your paper. List *at least* three, ideally academic, publications that you are planning to reference in your paper. Describe briefly, how the publications are related and relevant.
  
In case you are doing a literature review or survey list both, papers you are reviewing **and** some related work to your overall approach.

*Submission*: Add references and a description of their relevance in your paper. You must use whole sentences.

### Papers, related to my planned approach

I already mentioned these two papers in my previous submission, but here one more. 
They are thematically not related to birdsong analysis, but I like their structure and the way they are written. I plan to organize my survey paper in a similar way.

- "Object Detection in 20 Years: A Survey" - I like how it splits methods into clear categories based on technical approach and timeline. It also has good summary tables and visuals to compare techniques.

- "Including Signed Languages in Natural Language Processing" - this paper has a clear overview of a specialized research area. I like the clean writing style and that there is balance between linguistic theory and technical detail, also how the authors link their survey to broader questions in NLP. I would like to try something similar in my paper - first introducing birdsong, giving some background and explaining why it is interesting and important field, then showing the current methods for its analysis using computational tools.

### Papers that I am going to use for the survey

I would say that the type of papers can be divided in two main groups - biological studies and computer science.
The first can provide background on what birdsongs are and how they work, and the second group focuses on the methods for analyzing birdsong using different computational methods - machine learning, deep learning, etc.

### Biology and Linguistics Background

#### Songs to syntax: the linguistics of birdsong, Berwick et al., 2011

The papers consists of very nice explanations of the linguistic parallels between human speech and birdsongs. Also, it provides a good explanation of the birdsong structure, which I will use in my survey paper.

Link: https://web.mit.edu/6.034/www/6.s063/final-paper/birdsong.pdf

#### Birdsong and Human Speech: Common Themes and Mechanisms" – Doupe & Kuhl, 1999

Very foundational review, which explores the similarities between birdsong and human speech, including developmental stages, neural circuitry, and critical periods for learning. There is definitely a lot of information, which is out-of-scope for my paper, but I would like to cite some of the sections about speech and song production, structure of the birdsong, vocal learning, etc.

Link: https://ilabs.uw.edu/sites/default/files/2008%20and%201999%20Doupe%20and%20Kuhl.pdf

### Computational Methods

#### Automated annotation of birdsong with a neural network that segments spectrograms, Cohen et al., 2022

It is one of the most recent and major works in the field of using computational methods for birdsong analysis and they achieve significant results, using single neural network model (TweetyNet) that segments spectrograms of birdsong into annotated syllables. It was also on of the first papers that I found for the topic and the one I started my research with.

Link: https://elifesciences.org/articles/63853

#### TweetyBERT

Some of the authors are the same as in the TweetyNet paper. It is a follow-up, which builds on the TweetyNet approach to segment birdsong spectrograms, but they use transformers instead of convolutional models. In contrast to TweetyNet, the authors say that no human-labeled data is required for training, and they utilize transformer models, because they are usually very good at capturing complex temporal relationships among elements within sequences.

Link: https://www.biorxiv.org/content/10.1101/2025.04.09.648029v1.full.pdf

#### Fast and accurate annotation of acoustic signals with deep neural networks, Steinfath et al., 2021

This paper presents a different approach from the spectrogram-based methods. Authors also discuss the drawbacks of the spectrogram method. They say that their model, called DAS, learns a task-specific representation of sound features using temporal convolutional networks (TCNs). It needs very little manual data annotations (semi-supervised) - according to the authors small or moderate amounts of manual annotations suffice for adapting the method to a new species and annotation work can be simplified by combining DAS with unsupervised methods.

Link: https://elifesciences.org/articles/68837

#### Semi-Automatic Classification of Birdsong Elements Using a Linear Support Vector Machine, Tachibana et al., 2014

I will use this paper, because it is an example of a more "traditional" or "old-school" approach, not using deep neural networks, but SVM, since I will be doing some sort of comparison and grouping of different methods. It also shows how the field has been evolving. What can be definitely noticed in this approach is that the method includes major human labor for labelling and considers the human labels as always true.

Link: https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0092584

---
