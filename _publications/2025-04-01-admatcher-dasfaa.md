---
title: "ADMatcher: Self-supervised Subgraph Matching via Adaptive Dense-Aware Graph Contrastive Learning"
collection: publications
category: conferences
permalink: /publication/2025-04-01-admatcher-dasfaa
excerpt: 'We propose ADMatcher, a self-supervised subgraph matching framework using adaptive dense-aware graph contrastive learning.'
date: 2025-04-01
venue: 'DASFAA 2025 (CCF-B)'
slidesurl: '/files/ADMatcher_DASFAA_2025_slides.pdf'
paperurl: '/files/ADMatcher_DASFAA_2025.pdf'
bibtexurl: '/files/ADMatcher_DASFAA_2025.bib'
citation: 'Yan Hao, Du Lei, Gu Zhaoquan, et al. (2025). &quot;ADMatcher: Self-supervised Subgraph Matching via Adaptive Dense-Aware Graph Contrastive Learning.&quot; In <i>Proceedings of the 30th International Conference on Database Systems for Advanced Applications (DASFAA)</i>, 2025.'
---

**Authors:** Yan Hao, Du Lei, Gu Zhaoquan, et al.

**Venue:** The 30th International Conference on Database Systems for Advanced Applications (DASFAA), 2025. (CCF-B)

Links: [Paper](/files/ADMatcher_DASFAA_2025.pdf) · [Slides](/files/ADMatcher_DASFAA_2025_slides.pdf) · [BibTeX](/files/ADMatcher_DASFAA_2025.bib)

**Abstract:** Subgraph matching, which aims to determine whether a query graph is a substructure of a target graph, is a crucial problem in various domains.
However, subgraph matching is an NP-complete problem. Although prior studies have overcome the computational bottleneck as a supervised learning task, such methods are impractical for label-lacking real scenarios. Therefore, addressing the subgraph matching effectively under limited or without labels is still a key problem.
To tackle this problem, we propose ADMatcher, a self-supervised Subgraph Matching method via Adaptive Dense-Aware Graph Contrastive Learning (GCL).
We leverage GCL with adaptive augmentation and ensure the augmented graph is a subgraph of the original graph during augmentation stage to learn the subgraph relationship.
Specifically, as traditional stochastic augmentations may severely damage the intrinsic properties, we add three dense subgraph augmentation strategies to aware internal useful information. Furthermore, since general data augmentations often use manually selecting strategies, we adopt a min-max optimization method that adaptively adjusts the proportions of different augmentation strategies. Eventually, we redesign the encoder and train the model without labels in self-supervised way.
Experiments demonstrate that ADMatcher can outperform the supervised state-of-the-art method with uniformly distributed features, adaptively select better augmentation strategies, and achieve faster training and convergence.
