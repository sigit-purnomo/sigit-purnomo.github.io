---
title: "When Classical Models Compete with Deep Learning: A Semantic Label Transformation for Peer Feedback Classification"
excerpt: "This study proposes a semantic priority-based label transformation for Indonesian peer feedback classification and evaluates classical machine learning and deep learning models, emphasizing model stability, generalization, and evaluation under class imbalance."
date: 2026-10-08
permalink: /posts/2026/10/semantic-label-transformation-peer-feedback-classification/
categories: [publication]
tags: [peer-feedback, text-classification, machine-learning, deep-learning, label-transformation]
---

This article was published in the **2026 International Conference on Information Technology and Computing (ICITCOM)**, published by IEEE.

**Authors:** **Yohanes Sigit Purnomo W.P.**, Theresia Devi Indriasari

**Language:** English

**Abstract:** <br />
Peer feedback often contains overlapping communicative intents, making multi-label classification challenging. This study proposes a semantic priority-based label transformation that converts multi-label Indonesian peer feedback into a single-label task by assigning a dominant label based on communicative importance. The final transformed dataset consisted of 723 instances across four categories: Appreciation, Problem, Suggestion, and Neutral. Models were evaluated under class imbalance using weighted F1-score, balanced accuracy, and Matthews Correlation Coefficient. Results show that classical machine learning and deep learning models exhibit different performance characteristics. ExtraTrees with word-level TF-IDF achieved stable and competitive performance across evaluation stages, while Transformer-based models obtained higher cross-validation performance but lower validation performance, indicating a generalization gap. RCNN_WE achieved the highest validation performance, but its lower cross-validation score suggests sensitivity to data partitioning rather than definitive evidence of stronger generalization. The priority-order ablation supports the proposed Problem > Suggestion > Appreciation > Neutral order because it achieved the best-balanced performance, despite an Appreciation-first order producing higher weighted F1-score. These findings highlight the importance of label design, class imbalance, and evaluation strategy in automated peer feedback classification.

**Keywords:** Peer feedback classification, Semantic label transformation, Multi-label to single-label classification, Machine learning, Deep learning, Text classification, Class imbalance

**Conference:** 2026 International Conference on Information Technology and Computing (ICITCOM)

**Conference Date:** August 5, 2026

**Date Added to IEEE Xplore:** October 8, 2026

**Publisher:** IEEE

**Electronic ISBN:** 979-8-3195-3459-0

**Print on Demand ISBN:** 979-8-3195-3460-6

**DOI:** [10.1109/ICITCOM70739.2026.11714417](https://doi.org/10.1109/ICITCOM70739.2026.11714417)

**Article URL:** [https://ieeexplore.ieee.org/document/11714417](https://ieeexplore.ieee.org/document/11714417)

## How to Cite

If you extend or use this work, please cite the paper where it was introduced:

```bibtex
@inproceedings{Purnomo2026SemanticLabel,
    author = {Purnomo W.P., Yohanes Sigit and Indriasari, Theresia Devi},
    title = {When Classical Models Compete with Deep Learning: A Semantic Label Transformation for Peer Feedback Classification},
    booktitle = {2026 International Conference on Information Technology and Computing (ICITCOM)},
    year = {2026},
    publisher = {IEEE},
    isbn = {979-8-3195-3459-0},
    doi = {10.1109/ICITCOM70739.2026.11714417},
    url = {https://ieeexplore.ieee.org/document/11714417}
}
```
