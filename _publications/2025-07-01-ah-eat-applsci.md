---
title: "Adversarial Hierarchical-Aware Edge Attention Learning Method for Network Intrusion Detection"
collection: publications
category: manuscripts
permalink: /publication/2025-07-01-ah-eat-applsci
excerpt: 'We present an adversarial hierarchical-aware edge attention learning method for robust network intrusion detection.'
date: 2025-07-01
venue: 'Applied Sciences'
slidesurl: '/files/AH-EAT_slides.pdf'
paperurl: '/files/AH-EAT_AppliedSciences_2025.pdf'
bibtexurl: '/files/AH-EAT_AppliedSciences_2025.bib'
citation: 'Yan Hao, Du Lei, Gu Zhaoquan, et al. (2025). &quot;Adversarial Hierarchical-Aware Edge Attention Learning Method for Network Intrusion Detection.&quot; <i>Applied Sciences</i>. 15(14): 7915.'
---

**Authors:** Yan Hao, Du Lei, Gu Zhaoquan, et al.

**Venue:** Applied Sciences, 2025, 15(14): 7915.

Links: [Paper](/files/AH-EAT_AppliedSciences_2025.pdf) · [Slides](/files/AH-EAT_slides.pdf) · [BibTeX](/files/AH-EAT_AppliedSciences_2025.bib)

**Abstract:** The rapid development of information technology has made cyberspace security even more serious.
Network intrusion detection method is a practical scheme to protect network systems from cyberattacks.
However, as network flows have natural topological relationships and anomaly detection cannot simultaneously detect the attack types, the existing detection methods cannot handle these challenges in the real world.
To handle these problems, we propose a graph neural network based network intrusion detection method called Adversarial Hierarchical-Aware Edge Attention Learning Method (AH-EAT for short), which can utilize computer networks naturally exhibiting a graph structure with robust and multi-grained intrusion detection ability.
AH-EAT includes an edge-based graph attention mechanism embedding module, a hierarchical multi-grained detection module and an adversarial training module. 
The edge-based graph attention mechanism embedding module adopts graph attention networks to aggregate node and edge features according to their importance, effectively capturing key topological structural information.
Moreover, unlike traditional anomaly detection methods, the hierarchical multi-grained detection module uses coarse-grained detection to distinguish malicious and benign flow, while fine-grained classification identifies specific attack types simultaneously.
Specifically, the adversarial training module uses projected gradient descent to generate adversarial edge perturbations during training, which improves robustness and resilience to evasion attacks.
We conduct extensive experiments on four popular network intrusion detection benchmark datasets and the results demonstrate that AH-EAT outperforms state-of-the-art methods, achieving higher accuracy in multi-grained detection and robustness in both standard and adversarial scenarios.
