---
layout: page
title: Manufacturing Automation
description: 
img: assets/img/project-placeholder.svg
importance: 3
category: Active Projects
related_publications: true
---
This research develops learning-based methods for end-to-end manufacturing automation, connecting high-level design intent to executable fabrication processes. We study how foundation models can bridge CAD generation and CAM execution under geometric, physical, and process constraints, enabling structured and verifiable manufacturing pipelines.

**CAD: STEP-LLM (DATE 2026).**  
We develop STEP-LLM, a structured generation framework that translates natural-language design intent into valid ISO 10303 STEP CAD representations. Instead of treating CAD generation as free-form text output, we model STEP files as graph-structured entity sequences and design serialization strategies that preserve topological and geometric consistency. The system integrates retrieval-augmented generation to ground predictions in real CAD structures and applies reinforcement learning with geometry-aware rewards, such as renderability and geometric distance metrics, to improve structural validity. STEP-LLM demonstrates that large language models can generate manufacturing-ready CAD artifacts with high renderability and reduced geometric error.

**CAM: Vision-Language Models for English-Wheel Automation.**  
We extend the pipeline to downstream fabrication by studying toolpath auto-generation and optimization for English-wheel sheet forming. Given target deformation profiles or visual specifications, we train vision-language models to predict structured toolpaths that control robot end-effector trajectories under physical constraints. The system models deformation in the y–z plane and learns multi-cycle toolpaths that progressively approximate target shapes while respecting clamping and material behavior. We further investigate optimization strategies that reduce geometric deviation and forming inefficiency, connecting learned perception with executable manufacturing control.
