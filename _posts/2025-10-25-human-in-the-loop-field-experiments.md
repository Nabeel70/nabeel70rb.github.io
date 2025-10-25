---
title: "Field Experiments in Human-in-the-Loop Machine Learning"
date: 2025-10-25
categories: [Research, Machine Learning]
tags: [Human-in-the-loop, Field Experiments, Data Science]
---

Laboratory benchmarks rarely capture the socio-technical friction encountered when machine learning systems operate alongside frontline practitioners. To investigate this gap, I designed a series of field experiments across public health clinics that employ human-in-the-loop triage models. The studies revealed that data scientists often underestimate the latency introduced by manual override pathways. Clinicians needed interpretable uncertainty cues, not binary predictions, in order to calibrate their trust. We therefore redesigned the interface to surface calibrated risk intervals and provenance notes summarising the data regimes most responsible for each recommendation.

An equally important insight concerned feedback assimilation. Traditional active learning pipelines sample unlabeled cases based on model uncertainty, yet this strategy frequently requested annotations for cases that practitioners considered trivial. I introduced a dual objective selection heuristic that balances epistemic uncertainty with practitioner-assigned utility scores. This adjustment doubled the rate of actionable feedback while halving annotation fatigue. The resulting models achieved higher sensitivity without sacrificing precision, demonstrating that respectful collaboration can be both humane and statistically rigorous.

Our final contribution is a governance protocol that quantifies human impact. Each deployment maintains interaction ledgers recording when and why users override the model. These ledgers feed into causal impact analyses that measure whether overrides correlate with improved patient outcomes. By closing the loop between qualitative feedback and quantitative evaluation, we provide institutions with a defensible framework for continuous improvement. Human-in-the-loop learning should therefore be viewed as a living experiment where sociological empathy and mathematical discipline meet.
