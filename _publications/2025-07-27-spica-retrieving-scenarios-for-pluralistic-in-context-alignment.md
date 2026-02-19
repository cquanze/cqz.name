---
title: "SPICA: Retrieving Scenarios for Pluralistic In-Context Alignment"
venue: "ACL Findings"
year: 2025

link: "https://aclanthology.org/2025.findings-acl.41/"
doi: "10.18653/v1/2025.findings-acl.41"
pdf: "https://aclanthology.org/2025.findings-acl.41.pdf"
code: "https://github.com/Social-Futures-Lab/SPICA-code"
arxiv: "https://arxiv.org/abs/2411.10912"
preprint: false
authors:
  - name: Quan Ze Chen
    flags: [ "me" ]
  - name: K.J. Kevin Feng
  - name: Chan Young Park
  - name: Amy X. Zhang
---

When different groups’ values differ, one approach to model alignment is to steer models at inference time towards each group’s preferences. However, techniques like in-context learning only consider similarity when drawing few-shot examples and not cross-group differences in values. We propose SPICA, a framework that accounts for group-level differences during in-context example retrieval. SPICA introduces three designs: scenario banks, group-informed retrieval metrics, and in-context alignment prompts. From an evaluation of SPICA on an alignment task collecting inputs from four demographic groups (n = 544), our metrics retrieve in-context examples that more closely match observed preferences, with the best prompt configuration using multiple contrastive responses to demonstrate examples. In an end-to-end evaluation (n = 120), we observe that SPICA is higher rated than similarity-based retrieval, with groups seeing up to a +0.16 point improvement on a 5 point scale. Additionally, gains from SPICA were more uniform, with all groups benefiting from alignment rather than only some. Finally, we find that while a group-agnostic approach can align to aggregated values, it is not most suited for divergent groups.
