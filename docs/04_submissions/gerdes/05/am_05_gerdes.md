---
layout: default
title: Session 05
nav_exclude: true
---

## Session 05 - Qualitative Research

> Disclaimer: Handed in late due to sickness 09/06/2025 - 13/06/2025 (sick certificate available upon request)

### Task 05.01 - Related Work

> selection

**NOMAD Projection[^1]**
[^1]: Duderstadt, B., Nussbaum, Z., and Maaten, L. van der. 2025. NOMAD Projection. http://arxiv.org/abs/2505.15511.

One integral paper by Nomic AI explaining their approach to dimensionality reduction (DR) from dense vectors into two-dimensional entries to power their Atlas map. While this work focuses on large scale GPU-driven DR, they also provide an accompanying GitHub repository to apply the approach. This could potentially serve as a way to benchmark my own dataset and provides the foundation to differentiate my work.

**Feature dimensionality reduction: a review[^2]**
[^2]: Jia, W., Sun, M., Lian, J., and Hou, S. 2022. Feature dimensionality reduction: a review. Complex & Intelligent Systems 8, 3, 2663–2693.

This paper offers a comprehensive overview of multiple DR techniques and their particular strengths and weaknesses. It can serve as a reference point to narrow down the concrete selection of models and techniques I will try myself before distilling these tests into a pipeline / framework.

**Towards a comprehensive evaluation of dimension reduction methods for transcriptomic data visualization[^3]**
[^3]: Huang, H., Wang, Y., Rudin, C., and Browne, E.P. 2022. Towards a comprehensive evaluation of dimension reduction methods for transcriptomic data visualization. Communications Biology 5, 1, 719.

Expanding on [^2], this entry compares multiple approaches to DR as well. However, the evaluation criteria here are more precise while the work offers less of an overview. The used metrics here can be used as a benchmarking foundation to assess similar factors in my own resulting dataset.

> full preliminary bibliography (contains unfinished entries; might not be part of final paper)

- Data Maps, Part 1: Get Close With Data. https://www.nomic.ai/blog/posts/data-mapping.
- Duderstadt, B., Mulyar, A., Schmidt, B., et al. Atlas Whitepaper: Scalable Information Cartography. .
- Ghodsi, A. 2006. Dimensionality Reduction A Short Tutorial. .
- Moon, K.R., Van Dijk, D., Wang, Z., et al. 2019. Visualizing structure and transitions in high-dimensional biological data. Nature Biotechnology 37, 12, 1482–1492.
- Ourednik, A. 2022. Text2Landscape: Visualize a Text in Multiple Spaces with R — Force-directed networks, Biofabric, Word Embeddings, Principal Component Analysis and Self-Organizing Maps. Maps and Spaces. https://ourednik.info/maps/2022/02/04/text2landscape-visualize-a-text-in-multiple-spaces-with-r-network-visualization-word-embeddings-principal-component-analysis-and-self-organizing-maps/.
- Pennington, J., Socher, R., and Manning, C. 2014. Glove: Global Vectors for Word Representation. Proceedings of the 2014 Conference on Empirical Methods in Natural Language Processing (EMNLP), Association for Computational Linguistics, 1532–1543.
- Poličar, P.G., Stražar, M., and Zupan, B. 2023. Embedding to reference t-SNE space addresses batch effects in single-cell classification. Machine Learning 112, 2, 721–740.
- Růžička, M., Novotný, V., Sojka, P., Pomikálek, J., and Řehůřek, R. Flexible Similarity Search of Semantic Vectors Using Fulltext Search Engines. .
- Smilkov, D., Thorat, N., Nicholson, C., Reif, E., Viégas, F.B., and Wattenberg, M. 2016. Embedding Projector: Interactive Visualization and Interpretation of Embeddings. http://arxiv.org/abs/1611.05469.
- Sorzano, C.O.S., Vargas, J., and Montano, A.P. 2014. A survey of dimensionality reduction techniques. https://arxiv.org/abs/1403.2877.
- Velliangiri, S., Alagumuthukrishnan, S., and Thankumar joseph, S.I. 2019. A Review of Dimensionality Reduction Techniques for Efficient Computation. Procedia Computer Science 165, 104–111.
- wikimedia/wikipedia · Datasets at Hugging Face. 2025. https://huggingface.co/datasets/wikimedia/wikipedia.

#### prompts

more literature search: https://chatgpt.com/share/685181f6-cbe4-8008-b36b-d76ee2d8b92c
