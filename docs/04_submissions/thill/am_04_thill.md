---
layout: default
title: Session 04
nav_exclude: true
---

## Task 04.01 - Methodology Submission

**Title (tentative)**
Improving Fallacy Classification in Generative Models through Chain-of-Thought Reasoning Prompts

---

**Paper Structure and Methodology**

**1. Introduction**

* Introduce logical fallacies and their role in argumentation and online discourse.
* Outline the challenge of automated fallacy detection due to contextual and reasoning complexities.
* Present chain-of-thought (CoT) prompting as a promising technique for improving classification accuracy and explainability.
* Define the research question: *How can chain-of-thought reasoning prompts improve fallacy classification accuracy in generative models?*

**2. Related Work**

* Review prior research on:
  
     * Fallacy detection using machine learning and NLP.
     * The impact of CoT prompting on generative model reasoning.
     * Benchmarks and datasets relevant to fallacy detection (e.g., MAFALDA and others).

* Identify gaps and motivations for the current study.

**3. Methodology**

**3.1 Dataset and Benchmark Selection**

* Search for and assess existing fallacy detection datasets (e.g., MAFALDA, among others).
* Actively collect and curate a diverse set of online debates (e.g., from YouTube, podcasts, debate platforms) to construct a real-world evaluation corpus.
* Optionally annotate a small subset manually to focus on specific fallacy types.

**3.2 Model Architecture and Setup**

* Employ multiple generative models (e.g., OpenAI GPT models or similar).

* Build an evaluation pipeline using LangChain to orchestrate:
  
     * Automatic transcription of debate content.
     * Fallacy detection with and without CoT prompting.

* Develop a lightweight desktop application to manage and run evaluations.

**3.3 Prompting Strategies**

* Design baseline prompts for direct fallacy classification.
* Develop CoT prompts that guide models through intermediate reasoning steps before classification.
* Experiment with different CoT prompt variants to analyze their effects on reasoning and accuracy.

**3.4 Evaluation Procedure**

* Evaluate models on:
  
     * Classification accuracy.
     * Explanation quality (where applicable).

* Use both benchmark datasets and the curated online debate dataset for evaluation.

* Apply automatic metrics alongside limited manual evaluation to assess the reasoning chains and output quality.

**4. Results**

* Present quantitative comparison of performance between CoT-prompted and baseline models.
* Provide qualitative analysis of model-generated reasoning steps.

**5. Discussion**

* Reflect on the effectiveness of CoT prompting for fallacy detection.
* Discuss encountered challenges, such as prompt design and dataset limitations.
* Explore potential applications in moderation tools, educational contexts, or debate platforms.

**6. Conclusion and Future Work**

* Summarize key findings.
* Suggest directions for further research, including larger-scale evaluations, expanded fallacy taxonomies, and model fine-tuning for enhanced reasoning capabilities.


   
---
Feedback Lena:
* Rather not use the generic title of "Methodology" but some project specific term, e.g. "Fallacy Classification Improvement Pipeline".
* In papers (differently to theses) you focus on your "contributions" in the introduction, not explicitly on the research question. We will talk about this one more time in class at a later point.
* The structure and bullet points read well but I am a bit worried that it is too much content for a short paper. It could work but maybe already come up with a fallback plan of which part you could reduce, only describe very briefly, etc.


---
Feedback Alex:
- Well organised, but I also feel it is too much... Two points that I would cut out/greatly reduce/leave for a future project would be:
    
  (a) “Actively collect and curate a diverse set of online debates (e.g., from YouTube, podcasts, debate platforms) to construct a real-world evaluation corpus.” - Yes but outside the scope of a paper. Better to try out on one YouTube video perhaps, or one Podcast.
    
  (b) “Develop a lightweight desktop application to manage and run evaluations.” - Again, a nice idea but not core to the research and therefore outside the scope of the paper. File under future development.  
