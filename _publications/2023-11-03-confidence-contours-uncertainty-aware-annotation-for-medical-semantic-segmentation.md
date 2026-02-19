---
title: "Confidence Contours: Uncertainty-Aware Annotation for Medical Semantic Segmentation"
venue: "HCOMP"
year: 2023

link: "https://ojs.aaai.org/index.php/HCOMP/article/view/27559"
doi: "10.1609/hcomp.v11i1.27559"
pdf: "https://ojs.aaai.org/index.php/HCOMP/article/view/27559/27332"
preprint: false
authors:
  - name: Andre Ye
  - name: Quan Ze Chen
    flags: [ "me" ]
  - name: Amy X. Zhang
---

Medical image segmentation modeling is a high-stakes task where understanding of uncertainty is crucial for addressing visual ambiguity. Prior work has developed segmentation models utilizing probabilistic or generative mechanisms to infer uncertainty from labels where annotators draw a singular boundary. However, as these annotations cannot represent an individual annotator's uncertainty, models trained on them produce uncertainty maps that are difficult to interpret. We propose a novel segmentation representation, Confidence Contours, which uses high- and low-confidence ``contours’’ to capture uncertainty directly, and develop a novel annotation system for collecting contours. We conduct an evaluation on the Lung Image Dataset Consortium (LIDC) and a synthetic dataset. From an annotation study with 30 participants, results show that Confidence Contours provide high representative capacity without considerably higher annotator effort. We also find that general-purpose segmentation models can learn Confidence Contours at the same performance level as standard singular annotations. Finally, from interviews with 5 medical experts, we find that Confidence Contour maps are more interpretable than Bayesian maps due to representation of structural uncertainty.
