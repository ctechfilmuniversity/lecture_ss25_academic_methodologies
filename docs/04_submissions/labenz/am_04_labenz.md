---
layout: default
title: Homework
nav_exclude: true
---

## Task 04.01 - Methodology

### 1. Introduction

• Motivation: Digital 3D maps often display rooftops from a bird’s-eye view—facades visible in real life remain hidden.
• Problem: Users struggle to mentally align these maps with their physical surroundings.
• Contribution: We propose a novel focus+context technique where building facades tilt away from a user-defined focus point (e.g., current location), making visible real-world features that are otherwise occluded.
• Research Question: Does adaptive facade tilting improve users’ ability to cognitively transfer digital map information to real-world navigation tasks?

### 2. Related Work (Condensed)

• Focus+context visualization in 2D and 3D (e.g., fisheye views, 3D exaggeration)
• 3D building models in navigation (e.g., Google Maps, Mapbox GL)
• Spatial cognition: mental mapping, use of landmarks in wayfinding

### 3. Proposed Technique

• Adaptive tilting of building facades based on distance and angle from user’s viewpoint
• Reveals vertical architectural features (doors, windows, signs) while maintaining an overhead map context
• Implementation via WebGL prototype using simplified 3D geometry or point cloud approximations

### 4. Evaluation

• Design: Within-subject user study with two map conditions:
• A: Standard 3D map (flat rooftops)
• B: Adaptive tilting of facades
• Task: Participants identify a specific target (e.g., a café) within the map interface
• Participants: ~10 users, recruited from university context
• Metrics:
• Task success rate and completion time
• Subjective ratings (e.g., ease of orientation, clarity)

### 5. Analysis & Discussion

• Quantitative comparison of both conditions
• Initial insights into whether tilted facades support visual alignment with real-world landmarks
• Limitations:
• Small sample size
• Simplified test environment
• Prototype uses abstracted building geometry

### 6. Conclusion

• Early evidence suggests that adaptive facade tilting can help bridge the perceptual gap between map views and physical space
• Future work: Real-world testing with LiDAR data, mobile AR integration, and more complex urban scenes
