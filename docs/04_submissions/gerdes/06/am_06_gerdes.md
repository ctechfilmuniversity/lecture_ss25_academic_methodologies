---
layout: default
title: Session 06
nav_exclude: true
---

## Session 06 - Quantitative Research

### Task 06.01 - Introduction

Write the introduction for your paper. You do not need to re-use this introduction later for your actual paper - but you should! You can re-cap in [Chapter - Academic Writing](../../02_scripts/am_03_writing_script.md#the-introduction) what the introduction is about.

**Do not use a GenAi Tool for this task, as it is about practicing to write.**  
After all learning to write, is learning to think...

_Submission_: Your introduction - no need to use the paper template yet but you can make the submission with a markdown file.

---

> structuring

As a first step I will update the keywords on structure from session 04 (introduction section only):

[_Introduction_]

- _What is the problem?_
  - approximating dimensionality reduction for specific data domains using predictive modeling
- _Why is the problem important?_
  - [maintaining a personalized & verified collection of information becomes increasingly valuable]
    - [need to organize in order to navigate collection]
    - [knowledge organization / visual navigation]
    - [relate new data to existing entries]
- _What has so far been done on the problem?_
  - established techniques (UMAP, t-SNE, PCA) rely on the complete dataset to be present upfront
  - parameterized UMAP
  - wikipedia map by Nomic
- _What is the contribution of the paper on the problem?_\*
  - proposed approach [_Is the contribution original?_]
    - learning a dimensionality reduction distribution from traditional pipelines (semantic embedding → dimensionality reduction; teacher-student distillation)
    - simplified supervised predictive modeling task
    - requires a large dataset with mappings between input data (raw tokens) and reduced dimensionality (2D position for spatial relationships) [_Is the contribution non-trivial?_]
  - contributions
    - comparing selected traditional approaches to dimensionality reduction that are used for visualization of text data
    - proposing a pipeline for generating such a dataset mapping text tokens to 2D positions
    - evaluating and benchmarking a dataset generated using the pipeline

> introduction

Dimensionality reduction techniques such as PCA, t-SNE, and UMAP are widely used to visualize high-dimensional data, enabling intuitive exploration of complex datasets. However, these methods typically require access to the entire dataset in advance, limiting their applicability in dynamic environments where new data is continuously added. This paper addresses part of the challenge of approximating such dimensionality reduction methods for specific data domains using predictive modeling.

We propose an approach that learns to predict low-dimensional coordinates for raw token inputs by leveraging semantic embeddings followed by traditional dimensionality reduction. This supervised learning approach reduces computational overhead and supports incremental data addition. As a first step towards training such a model, this paper incorporates the following contributions:

- A comparison of selected dimensionality reduction techniques commonly used for visualizing text data, along with a brief analysis of their strengths and limitations in generating interpretable 2D embeddings (Section 01)
- A reproducible pipeline for constructing datasets that map text tokens to 2D coordinates using semantic embeddings and traditional dimensionality reduction methods (Section 02)
- An evaluation of the generated dataset using common dataset quality metrics (Section 03)

### Arisen Questions

- [ ] Is _What is the contribution of the paper on the problem?_\* supposed to be the list of contributions mentioned in the script?
- [ ] Are _Is the contribution original?_ and _Is the contribution non-trivial?_ sufficiently addressed? If not, how and where could that be deepened?
- [ ] I found a paper[^1] by Nomic (preprint currently) where they discuss their approach to dimensionality reduction. Since their approach focuses on parallelization I think the differentiation could now be part of the _related work_ section after all. Do you agree?
- [ ] I know we discussed that in class but I can't surely remember wether we are supposed to use the active "we" (l.51) or if we should keep the perspective neutral ("this paper ..." etc.)
- [ ] The part for _Why is the problem important?_ was difficult for me. I opted to focus on the technical improvement to be able to handle incremental additions but I am unsure wether this is sufficient.

[^1]: Duderstadt, B., Nussbaum, Z., and Maaten, L. van der. 2025. NOMAD Projection. http://arxiv.org/abs/2505.15511.
