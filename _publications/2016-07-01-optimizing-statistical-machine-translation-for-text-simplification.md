---
title: "Optimizing Statistical Machine Translation for Simplification"
venue: "ACL"
year: 2016

link: "https://aclanthology.org/Q16-1029/"
doi: "10.1162/tacl_a_00107"
pdf: "https://aclanthology.org/Q16-1029.pdf"
code: "https://github.com/cocoxu/simplification"
preprint: false
authors:
  - name: Wei Xu
  - name: Courtney Napoles
  - name: Ellie Pavlick
  - name: Quan Ze Chen
    flags: [ "me" ]
  - name: Chris Callison-Burch
---

Most recent sentence simplification systems use basic machine translation models to learn lexical and syntactic paraphrases from a manually simplified parallel corpus. These methods are limited by the quality and quantity of manually simplified corpora, which are expensive to build. In this paper, we conduct an in-depth adaptation of statistical machine translation to perform text simplification, taking advantage of large-scale paraphrases learned from bilingual texts and a small amount of manual simplifications with multiple references. Our work is the first to design automatic metrics that are effective for tuning and evaluating simplification systems, which will facilitate iterative development for this task.
