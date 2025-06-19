---
layout: default
title: Homework
nav_exclude: true
---


# 06.01 Introduction

## Task

Write the introduction for your paper. You do not need to re-use this introduction later for your actual paper - but you should! You can re-cap in Chapter - Academic Writing what the introduction is about.

Do not use a GenAi Tool for this task, as it is about practicing to write.
After all learning to write, is learning to think…

Submission: Your introduction - no need to use the paper template yet but you can make the submission with a markdown file.

## Structure

**1. Context and Motivation (2–3 sentences)**

- Explaining why fallacies are relevant today.

- Mention the prevalence of fallacious reasoning in public and online debates (political rhetoric, social media, etc.). 

- Emphasise their persuasive nature and the challenges they pose to critical dialogue and AI systems alike.

References:

- Jin et al. (2022) for a general claim about their complexity and their role in online discourse.

- Habernal et al. (2018) for social dynamics of fallacies in web argumentation.

**2. Problem Statement (2 sentences)**

- Explaining what the technical or conceptual difficulties are.

-Fallacy detection is hard for machines due to context, implicit premises, overlapping categories, etc.

- Existing benchmarks and methods struggle with this nuance.

References:

Jin et al. (2022): Contextual ambiguity and overlapping categories.

(Li et al., 2024): (FLUB benchmark) They show examples where even recent models fail systematically on diverse fallacy types.

**3. Contribution and Research Focus (3–4 sentences)**

- What am I doing about this?

- Present chain-of-thought prompting as a promising method to improve reasoning.

- Your contribution is testing CoT for fallacy classification in generative models.

- Frame this as a targeted experiment, using a real-world debate case study (Kirk vs Cambridge, or Peterson vs 20 Atheists).

- Optionally mention the Dillahunty analysis as an expert reference point for qualitative comparison.

References:

- Wei et al. (2022): Chain-of-thought prompting boosts performance on reasoning-heavy tasks.

- Matt Dillahunty video (paraphrased as “expert analysis” of argumentation quality and fallacies).


**4. Closing Sentence (1 sentence)**

- Bridge into the rest of the paper

- Indicating the paper’s structure or its aim in evaluating the method’s effectiveness.

## Introduction

Online debates having as goal consensus building and educating on different sides of problems are attracting the attantion of an increasing amount of people but the gaps between opposing points of views still seem to grow larger as time progresses. One phenomenon that still nurters this widening lies within the biases each indiviual withholds as well as the practice of fallacious argumentation that result from these biases. In addition to it being used as a result of one's biases, it also get's used as a means of manipulation as can be observed in many political discourses as well as in all kinds of arguments across the spectrum of interpersonal exchanges. Several promising counter-measures are increasingly getting developed and implemented such as live fact-checking and ML-based approaches.  While recent advancements in NLP (Natural language progressing) have come a long way, automated fallacy detection however remains a difficult task due to the context-dependant and nuanced nature of argumentative language (Jin et al., 2022). Further difficulties lie within the nature of human reasoning which is tied to different sets of premises (presuppositions, axioms, paradigms, etc.) and within the fact that we have overlapping categories of fallacies which in many instances undermines a clear categorisation. Several existing papers are dedicated to solving these issues. Wei et al. showed that chain-of-thought reasoning can be applied within NLP to ameliorate the evalutaion of different reasoning problems.

In summary, this paper makes the following contributions:
- Case study, where the findings around the research on Chain-of-thought prompting gets applied to the evaluation of X real world examples of a specif form of debates.
- The results get crossreferenced with expert analysis
- Further tuning of Cot tailored to the case study

...to be corrected and finished

## References

**Papers:**

- Jin et al. (2022) – [Logical Fallacy Detection - ACL Anthology](https://aclanthology.org/2022.findings-emnlp.532/)

- Wei et al. (2022) – [ Chain-of-Thought Prompting Elicits Reasoning in Large Language Models](https://arxiv.org/abs/2201.11903)
   
- Li et al. (2024) – [When LLMs Meet Cunning Texts: A Fallacy Understanding Benchmark for Large Language Models](https://arxiv.org/abs/2402.11100)

- Habernal et al. (2018) - [Before Name-Calling: Dynamics and Triggers of Ad Hominem Fallacies in Web Argumentation](https://aclanthology.org/N18-1036/)

**Debates:**

- [Charlie Kirk + Q&A / Debate | Cambridge Union](https://www.youtube.com/watch?v=dkiM-z0Mzyg&t=38s)

- [Jordan Peterson vs 20 Atheists | Surrounded](https://www.youtube.com/watch?v=Pwk5MPE_6zE&t=3082s)

**Expert Reference:**

- [Matthew Dillahunty reacts to Jordan Peterson vs 20 Atheists](https://www.youtube.com/watch?v=bYifYb2KkVA&t=2672s)


