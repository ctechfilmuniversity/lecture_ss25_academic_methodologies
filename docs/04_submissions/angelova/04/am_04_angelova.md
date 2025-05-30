---
layout: default
title: Homework
nav_exclude: true
---

**Academic Methodologies**
  
Prof. Dr. Lena Gieseke \| l.gieseke@filmuniversitaet.de \| Film University Babelsberg KONRAD WOLF
Alexander Walmsley \| a.walmsley@filmuniversitaet.de \| Film University Babelsberg KONRAD WOLF

## Session 04 - Reasoning

* [Your Paper](#your-paper)
    * [Task 04.01 - Methodology](#task-0401---methodology)

## Your Paper

### Task 04.01 - Methodology

Deadline: June 5th


It is time to think about how you want to answer the question(s) you are posing.  

Brainstorm which methods and/or which steps you want to apply. This task does not aim to find your personal journey of investigation. You should work on defining the approach that you will present in a paper as your methodology (but of course, you can also reflect on what you, personally, need to do to get there). 

Write down your methodology as overall paper structure (sections) and bullet points for each section.

### Structure

A am writing a survey/ review paper on computational methods for birdsong analysis, therefore during my research I try to collect and skim/read different survey papers to get a feeling and also inspiration about the structure.
Here are some examples of papers that I like and think that they will be helpful for my survey paper:

- "Object Detection in 20 Years: A Survey" 
- "Including Signed Languages in Natural Language Processing" 
- ...

__1 Introduction__
- why is the field important

    - birdsong syllables are order according to complex sequential rules, therefore provide a model to study systems, which generate sequential behaviors like the human speech
    - the segmentation step is a laborious task requiring human effort and prone to human error and bias
    - many methods need labeled datasets or some isolated syllabled after human-aided segmentation 
    - no globally known rules for birdsong syntax!
    - thresholding algorithms not very reliable - fail especially for complex bird songs 
    - syllables labelling procedure cannot be generalized acress datasets since syllable categories are defined for eahc individual eparatelly [Ghaffari et al., 2023] 

Write about:
- scope of the paper - what specific area/ problem it covers
- what are the contribution of this survey
- paper structure summary 

The rest of this paper is organized as follows. In Section X we ... 

__2 Background/ Historical context?__

- Give a brief introduction of songbirds and their song structure 
- Give some summary/ overview of the process of birdsong annotation 
- briefly outline the evolution
- with this section set the stage
- highlight key shifts if any?

Write/ explain about the initial/ basic manual way of doing manual birdsong analysis by human experts

how typical birdsong annotation works - two steps - segmentation and labeling,  

from the paper "Song to syntax - the linguistics of birdsong"

- "syllable" is an uninterrupted sound, which consists of one or more coherent time-frequency traces, which are called "notes"
- "motifs" - repeated sequences of syllables
- "song bout" - continuous rendition of several motifs

Are there some distinct periods - like pre deep learning period and post deep learning period?

Or maybe structure the part like this:

- why is there a need for birdsong analysis
- what are the challenges
- what are the procedures when doing this
    - datasets
    - metrics
- approaches until now - and then in new section more information about the different types of approaches

__3 Classification of Methods or Approaches___

- maybe here propose a clear and useful structure - supervised and semi-supervised vs deep neural networks vs unsupervised

Very important to include about:

- datasets 
- metrics 

Where to write about datasets and metrics?

How can the existing methods be grouped together? Based on the algorithm/ models they use or based on being supervised/ unsupervised, based on the input - raw audio input vs spectrograms (maybe does not make much sense)

__4 Detailed survey of each category__

If I organize the existing research into group of method types, then here explain each group in more details.

If I decide to list key approaches until now - in this section go into more details about each type of approach.

- definition and overview of the category
- representative techniques/ major approaches
- comparison of methods in this category
- strengths, weaknesses, use cases
- same paragraphs structure for each category

__statistical models:__ they require huge amount of recordings in a controlled lab environment

Comparative analysis across categories
- how to categories differ or complement each other
- comparison table

__5 Open challenges and future directions__

- Outline/ summary of the main difficulties of the task 

Every paper talks about these difficulties - so summarize them - e.g. manual annotations, missing general models, etc. 

- Here something about the creative direction? 

__Conclusion__

---
