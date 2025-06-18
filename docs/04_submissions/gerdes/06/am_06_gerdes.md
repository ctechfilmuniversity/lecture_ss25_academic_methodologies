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
  - visualization of spatial-semantic relationships in text data
- _Why is the problem important?_
  - knowledge organization
  - learning
    - relate new information to existing knowledge
      - eg. more robust retention
- _What has so far been done on the problem?_
  - current techniques focus on data sorting after collecting the entire data or processing incoming batches
  - need for iterative dimensionality reduction
- _What is the contribution of the paper on the problem?_\*
  - proposed approach [_Is the contribution original?_]
    - learning a dimensionality reduction distribution from traditional pipeline (semantic embedding → dimensionality reduction)
    - simplified supervised predictive modeling task
    - requires a large dataset with mappings between input data (raw tokens) and reduced dimensionality (2D position for spatial relationships) [_Is the contribution non-trivial?_]
  - contributions
    - comparing selected traditional approaches to dimensionality reduction that are used for visualization of text data
    - developing a framework for generating such a dataset mapping text tokens to 2D positions
    - evaluating and benchmarking a dataset generated using the framework

> introduction

### Arisen Questions

- [ ] Is _What is the contribution of the paper on the problem?_\* supposed to be the list of contributions mentioned in the script?
- [ ] Are _Is the contribution original?_ and _Is the contribution non-trivial?_ sufficiently addressed? If not, how and where could that be deepened?
- [ ] I found a paper[^1] by Nomic (preprint currently) where they discuss their approach to dimensionality reduction. Since their approach focuses on parallelization I think the differentiation could now be part of the _related work_ section after all. Do you agree?

[^1]: Duderstadt, B., Nussbaum, Z., and Maaten, L. van der. 2025. NOMAD Projection. http://arxiv.org/abs/2505.15511.
