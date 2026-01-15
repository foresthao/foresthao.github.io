---
title: "ContrastMatcher: Adaptive Contrastive Provenance Graph Matching for Host-Based Attack Detection"
collection: publications
category: manuscripts
permalink: /publication/2025-01-15-contrastmatcher-iotj
excerpt: 'We propose ContrastMatcher, an adaptive contrastive provenance graph matching method for host-based attack detection.'
date: 2025-01-15
venue: 'IEEE Internet of Things Journal'
slidesurl: '/files/ContrastMatcher_slides.pdf'
paperurl: '/files/ContrastMatcher_IoTJ_2025.pdf'
bibtexurl: '/files/ContrastMatcher_IoTJ_2025.bib'
citation: 'Yan Hao, Liao Wenhao, Gu Zhaoquan, et al. (2025). &quot;ContrastMatcher: Adaptive Contrastive Provenance Graph Matching for Host-Based Attack Detection.&quot; <i>IEEE Internet of Things Journal</i>. doi: 10.1109/JIOT.2025.3633319.'
---

**Authors:** Yan Hao, Liao Wenhao, Gu Zhaoquan, et al.

**Venue:** IEEE Internet of Things Journal, 2025.  
**DOI:** 10.1109/JIOT.2025.3633319

Links: [Paper](/files/ContrastMatcher_IoTJ_2025.pdf) · [Slides](/files/ContrastMatcher_slides.pdf) · [BibTeX](/files/ContrastMatcher_IoTJ_2025.bib)

**Abstract:** Provenance graphs have emerged as a promising approach for detecting host-based attacks, particularly on Internet of Things (IoT) endpoints where audit logs are available but resources are constrained. Such graphs integrate fine-grained system audit logs and formulate the attack detection process as subgraph matching within the provenance graph. Existing methods relying on exact subgraph matching are computationally intensive and time-consuming, while supervised learning for approximate subgraph matching, although a potential alternative, requires extensive labeled data that is prohibitively costly for annotating provenance graphs at scale.
To tackle these problems, we propose **ContrastMatcher**, a self-supervised adaptive graph contrastive learning for provenance subgraph matching which needs no label for training. ContrastMatcher consists of three modules: reduction, adaptive self-supervised learning, and lightweight detection. By graph reduction and process-centric ego partitioning, the reduction module identifies likely regions where attacks may occur, substantially reducing computational complexity and runtime. The adaptive self-supervised learning module selects effective augmentations to learn the subgraph representations with a carefully designed self-attention encoder, enabling ContrastMatcher to work without any label. Finally, the lightweight detection module classifies the attack relations between each query and the candidates from the learned representations automatically, which avoids setting the approximation manually. Experiments on the DARPA Engagement~3 datasets show that ContrastMatcher can reduce irrelevant host-based log events by $80\%-90\%$. In addition, without any label in the provenance graph, it achieves a competitive performance regarding the detection accuracy with only $1\%$ training time compared to the existing supervised learning methods.
