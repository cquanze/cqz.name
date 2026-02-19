---
title: "Goldilocks: Consistent Crowdsourced Scalar Annotations with Relative Uncertainty"
venue: "CSCW"
year: 2021

link: "https://dl.acm.org/doi/abs/10.1145/3476076"
doi: "10.1145/3476076"
pdf: "https://dl.acm.org/doi/epdf/10.1145/3476076"
preprint: false
authors:
  - name: Quan Ze Chen
    flags: [ "me" ]
  - name: Daniel S. Weld
  - name: Amy X. Zhang
---

Human ratings have become a crucial resource for training and evaluating machine learning systems. However, traditional elicitation methods for absolute and comparative rating suffer from issues with consistency and often do not distinguish between uncertainty due to disagreement between annotators and ambiguity inherent to the item being rated. In this work, we present Goldilocks, a novel crowd rating elicitation technique for collecting calibrated scalar annotations that also distinguishes inherent ambiguity from inter-annotator disagreement. We introduce two main ideas: grounding absolute rating scales with examples and using a two-step bounding process to establish a range for an item's placement. We test our designs in three domains: judging toxicity of online comments, estimating satiety of food depicted in images, and estimating age based on portraits. We show that (1) Goldilocks can improve consistency in domains where interpretation of the scale is not universal, and that (2) representing items with ranges lets us simultaneously capture different sources of uncertainty leading to better estimates of pairwise relationship distributions.
