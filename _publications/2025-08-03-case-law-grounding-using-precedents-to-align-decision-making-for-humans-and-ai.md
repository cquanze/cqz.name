---
title: "Case Law Grounding: Using Precedents to Align Decision-Making for Humans and AI"
venue: "ACM CI"
year: 2025

link: "https://dl.acm.org/doi/10.1145/3715928.3737487"
doi: "10.1145/3715928.3737487"
pdf: "https://dl.acm.org/doi/pdf/10.1145/3715928.3737487"
preprint: false
authors:
  - name: Quan Ze Chen
    flags: [ "me" ]
  - name: Amy X. Zhang
---

From moderating content within an online community to producing socially-appropriate generative outputs, decision-making tasks—conducted by either humans or AI—often depend on subjective or socially-established criteria. To ensure such decisions are consistent, prevailing processes primarily make use of high-level rules and guidelines to ground decisions, similar to applying “constitutions” in the legal context. However, inconsistencies in specifying and interpreting constitutional grounding can lead to undesirable and even incorrect decisions being made. In this work, we introduce “case law grounding” (CLG)—an approach for grounding subjective decision-making using past decisions, similar to how precedents are used in case law. We present how this grounding approach can be implemented in both human and AI decision-making contexts, introducing both a human-led process and a large language model (LLM) prompting setup. Evaluating with five groups and communities across two decision-making task domains, we find that decisions produced with CLG were significantly more accurately aligned to ground truth in 4 out of 5 groups, achieving a 16.0–23.3 %-points higher accuracy in the human process, and 20.8–32.9 %-points higher with LLMs. We also examined the impact of different configurations with the retrieval window size and binding nature of decisions and find that binding decisions and larger retrieval windows were beneficial. Finally, we discuss the broader implications of using CLG to augment existing constitutional grounding when it comes to aligning human and AI decisions.
