---
layout: default
title: Session 03
nav_exclude: true
---

## Session 04 - Reasoning

## Your Paper

### Task 04.01 - Methodology

### Brainstorm

_overall_

- literature review
  - dimensionality reduction in terms of semantic proximity
    - pipeline
    - configuration
  - dataset generation
    - best practices
- framework development for dataset generation
- evaluation

---

_notes on structure_<br>
(focus on narrative, based on [am_03_writing_script.md](../../../02_scripts/am_03_writing_script.md))

> narrative

- Leitmotif
  - Here is a problem
    - visualizing semantic relationships between notes
  - It is an interesting problem
    - ability to generate a structured birds-eye perspective on personal notes collection
    - link new knowledge to existing knowledge for more robust retention
  - It is an unsolved problem
    - current techniques focus on data sorting after collecting the entire data or processing incoming batches
      - dimensionality reduction using supervised predictive modeling
        - requires a large dataset with mappings between input data (like text) and reduced dimensionality (2D for spatial relationships)
          - no such dataset available
  - **Here is my idea**
    - using existing DR techniques (eg. PCA, t-SNE and UMAP) to generate data set
      - general knowledge base (ie. wikipedia dataset) as text source
      - testing and evaluating multiple configurations
  - My idea works
    - dataset evaluation
      - common general quality measurements used for datasets
      - spatial structure of the resulting dataset when visualizing

> structuring

- [_Intro_]
  - problem: Visualizing semantic relationships between information
  - interest
    - ability to generate a structured birds-eye perspective on personal notes collection
    - relate new knowledge to existing knowledge for more robust retention
  - unresolved
    - current techniques focus on data sorting after collecting the entire data or processing incoming batches
      - dimensionality reduction using supervised predictive modeling
        - requires a large dataset with mappings between input data (like text) and reduced dimensionality (2D for spatial relationships)
          - no such dataset available -> How can we generate this data set?
- _Related Work_ (move that to main!)
  - dataset generation
    - best practices
  - dimensionality reduction in terms of semantic proximity
    - pipeline components
    - configuration
- _Main Content_
  - combining existing embedding (eg. sBERT, nomic-embed) and DR (eg. PCA, t-SNE and UMAP) techniques to generate data set
    - general knowledge base (ie. wikipedia dataset) as text source
    - testing and evaluating multiple configurations
  - Results
    - framework/pipeline for generating datasets based on mappings between high-dimensional and reduced (spatial) dimensional data
  - Evaluation
    - common general quality measurements used for datasets
    - spatial structure of the resulting dataset when visualizing
  - Discussion
- [_Future Work_]
  - usage of the dataset
    - model training

### Methodology

- _Abstract_
  - assumption about the dataset generation
- _Intro_
  - based on leitmotif-approach, kindle interest through outlining the problem
- _Related Work_ (analogous to **literature review**)
  - dataset generation in general
    - best practices: Papers that dealt with the generation of large-scale datasets; problems they encountered and solutions they came up with
  - dimensionality reduction in terms of semantic proximity
    - paper selection based on usability for
      - pipeline components
      - configuration
    - differentiation from "Nomic Atlas" (see `Q03`)
- _Main Content_
  - combining existing embedding (eg. sBERT, nomic-embed) and DR (eg. PCA, t-SNE and UMAP) techniques to generate data set
    - testing and evaluating multiple configurations
  - **Results**
    - comparison of different combination that have been tried out
      - framework/pipeline for generating datasets based on mappings between high-dimensional and reduced (spatial) dimensional data
  - **Evaluation**
    - common general quality measurements used for datasets (maybe should be part of literature review?)
    - spatial structure of the resulting dataset when visualizing (too similar too Nomic?)
  - **Discussion**
    - dependant on outcome
- _Conclusion_
  - dependant on outcome

### Arisen Questions

- [ ] `Q01:` The main reason the dataset generation is interesting, is the ability to train predictive models based on the new set. Due to scope this will not be part of the paper so naturally this would fall under "Future Work". Does the narrative structure still make sense this way?
- [ ] `Q02:` Intro feels disproportionate to the main content. Yes / No ?
- [ ] `Q03:` [Nomic Atlas](https://atlas.nomic.ai/discover) as related (and inspirational) but different work ([UMAP and proprietary algorithm](https://docs.nomic.ai/atlas/embeddings-and-retrieval/dimensionality-reduction)). Difference large enough? (similar (proprietary: nomic-project-v2) pipeline; result is not the visualization but new dataset) Would this rather be an Acknowledgement?




   
---
Feedback Lena:
* Don't use "Main Content" as section title, but use something project specific, e.g. "Adaptive Facade Tilting".
* Instead of "interest", I would use "application scenario"
* In papers (differently to theses) you already include your "contributions" in the introduction. We will talk about this one more time in class at a later point.
* Q1: Yes. It is a bit of a balance but manageable. I suggest that you do tell the larger story, including the training early on, e.g. already in the intro. But then you also need to make it crystal clear, what we gain from this specific paper already, without the later future work steps.
* Q2: No. Because of your "two step problem", you do need a bit more story telling, which is fine.
* Q3: I am not sure if I fully understand your questions. If something is related, either in academia or the industry, you should mention it and let your reader know how you are different or why it is worthwhile that you are "doing it again". Trying something with open source resources / algorithm is for our scope totally enough as story.
