---
layout: default
title: Session 01
nav_exclude: true
---

### Task 01.01 - Working With Literature

In the past I have had good experiences with `zotero`, so I will most likely stick with it. Since there is also a browser extension available, adding new literature is quick and easy while directories and tagging capabilities allow for a nicely organized bibliography: Currently, I have one folder per project (eg. knoto for all papers I collected during the time I worked on the first-term project). Inside, the content is organized using different tags, describing the categories of the resource. If there is a full PDF version of a paper available, it can be added to the entry in Zotero, allowing to write annotations and highlight phrases in the document directly within the application. While searching for phrases used in the annotations does work, the lack of highlighting the query occurrences makes searching through the library a bit harder than it needs to be. Because of this, once I am more familiar with the [LaTeX template](docs/01_sessions/01_introduction/acsfubPublStyle_2025.zip), I might consider switching to a pure `BibTeX` approach with more granular control over the desired features.

### Task 01.02 - Topic Brainstorming

- **knowledge organization (expansion to the first-term project)**
  - predictive, fixed dimensionality reduction -> research gap
    - t-SNE, UMAP etc. (existing dim reduction algorithms) work with the entire dataset or rearrange upon additions (data streaming approach)
    - no single entry approach available (at least not at first glance)
  - building an ml model from scratch (and synthetic data)
  - combination of theory and practice -> validate theoretical understanding with practical implementation
  - more nuanced approach to reading cs papers (eg. actually trying to understand at least some of the mathematical formulas)
- **graphics**
  - nerf/gs
    - how do nerfs work?
    - how does gaussian splatting work?
    - comparison between both
    - usage in vfx, movies
    - is the technology production ready? Where is it used already?
    - what tools are available? what is still missing?
- **politics**
  - risks through advancements in technology
    - radicalization in social networks
      - usage of bots -> usage of gen-ai to sway public opinion
      - digital communication as marketing tool during election cycles
    - data and privacy concerns with the current coalition treaty
    - influence of artificial data (gen-ai) on the usability/freedom of the internet
    - consequences in software development job market through heavy investment into ai, agents and agi
- **gaming**
  - narrative interactivity through gen-ai
    - can we build virtual worlds that develop interesting story-lines based on player action?
    - has this been done? (eg. [NVIDIA ACE](https://www.youtube.com/watch?v=psrXGPh80UM)) state of the art?
    - are there real products (games) where this actually works (ie. is fun not just a gimmick)
    - somewhat an infinite story?
    - speculative proceduralism in story-telling (No Man's Sky as a game that is almost fully procedural; what would this level of procedural story look like?)
      - would that even be desirable?


### Task 01.03 - Topic Selection

As I am planning on writing the paper as a theoretical portion of an implementation that I would like to submit for `machine learning one`, you can find a more detailed description on the [knoto homepage](https://knoto.whatphilipdoes.com/log/15-roadmap-term-2/). Because I would like to keep working on the application and this would allow for a nice tie-in with both ml-one (and also in parts academic reading two), my topic of choice is `1.`.

1. **Text to Space: A Supervised-Learning Approach to Semantic Coordinate Prediction**
   - interest / motivation
      - addressing a research gap
      - in conjunction with the practical part, a more universal learning experience 
      - relating to my prior first term project and acting as an expansion on the work I already put in
   - characteristics
      - in-depth literature review of existing work, addressing dimensionality reduction in fixed-size datasets (ie. PCA, UMAP and t-SNE)
      - architecture of a dataset generation pipeline
      - model architecture for a prediction algorithm
      - documentation of the training and model performance
   - questions
      - What are the currently available approaches to visualize semantic patterns as spatial relationships in textual datasets?
      - How do BERT-based models capture semantics from text input?
      - How does one generate a large dataset, mapping knowledge based texts (ie. encyclopedia-like content) to semantically coherent spatial coordinates?
      - Can such a dataset be used to train a model capable of making predictions for new texts in relation to the structures found in the training corpora?
      - How does a model built on this premise compare to a hybrid approach with a BERT embedding generator and a pre-trained UMAP reducer?
      - How do dataset size and training parameters influence model performance?
   - solutions
      - literature review of the current state-of-the art to distill models best suited for extracting the spatial structure from a dataset
      - deep-dive into the BERT (and Sentence-BERT) to establish an architectural understanding
      - using established algorithms like PCA, t-SNE or UMAP to generate a dataset based on the [wikipedia dataset](https://huggingface.co/datasets/wikimedia/wikipedia)
      - design and train a prediction model on the resulting dataset
      - benchmark against the existing pipeline found in `knoto` focusing on factors like inference speed, result accuracy, startup time and file size
2. **Procedural Interactive Story-Telling: A Qualitative Analysis of Generative Modeling as a Framework for Dynamic Narrative Experiences**
   - interest / motivation
      - possibility for a pending fundamental change in how narratives in video games work
      - implications for other fields (narrative design in exhibition contexts)
   - characteristics
      - literature review of current generative models used in interactive storytelling
      - analysis of existing commercial implementations and their reception
      - evaluation of technical constraints (local vs. cloud processing)
      - case studies of successful and unsuccessful implementations
   - questions
      - Are there commercial games already successfully implementing these techniques?
      - What makes a procedurally generated story compelling versus gimmicky?
      - How can these technologies be implemented regarding infrastructure?
        - Are remote LLMs the only possible approach to nuanced reactivity or is there a middle ground with more creative control for game designers and possibly the ability to run models locally?
        - In server-centered architectures, what are conceptual possibilities with shared storylines shaped by and adapted to multiple players?
      - Is an "infinite story" technically feasible and narratively desirable?
   - solutions
      - extensive review of research and demos with a focus on state-of-the-art approaches (such as [NVIDIA ACE](https://www.youtube.com/watch?v=psrXGPh80UM))
      - trying out and documenting existing implementations
      - taking a thorough look at limitations in other areas that might translate into this aspect as well
3. **Neural Rendering Strategies: A Review on Application and Usability within Virtual Effects and Virtual Production Pipelines**
   - interest / motivation
      - possible paradigm shift in rendering / set recreation
      - actually trying out the technology for myself and getting a grasp of what works and what does not
      - thematic closeness to film production and therefore the university context
   - characteristics
      - practical testing and documentation of available tools and workflows
      - comparison with traditional rendering pipelines in production environments
   - questions
      - How do NeRF and Gaussian Splatting fundamentally work?
      - What are the key technical differences and tradeoffs between these approaches?
      - What real-world applications already exist in VFX and virtual production?
      - What tools are currently available, and what crucial components are missing?
      - How might these technologies evolve to better serve needs in creative applications? 
   - solutions
      - extensive review of the relevant foundational literature (ie. [NeRF: Representing Scenes as Neural Radiance Fields for View Synthesis](https://doi.org/10.48550/arXiv.2003.08934) and [3D Gaussian Splatting for Real-Time Radiance Field Rendering](https://doi.org/10.48550/arXiv.2308.04079))
      - taking a look at the current state-of-the-art and describing development and optimizations that took place
      - trying out and documenting existing tools and implementations, comparing traditional 3D rendering (ie. ray-tracing) approaches and neural rendering
