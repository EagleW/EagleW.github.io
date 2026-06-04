---
title: "Describing a Knowledge Base"
collection: publications
permalink: /publication/narrating
date: 2018-9-7
venue: 'The 11th International Conference on Natural Language Generation (INLG 2018)'
citation: '<u><b>Qingyun Wang</b></u>, Xiaoman Pan, Lifu Huang, Boliang Zhang, Zhiying Jiang, Heng Ji, Kevin Knight (2018). <b>Describing a Knowledge Base</b><i> in Proceedings of the 11th International Conference on Natural Language Generation</i>. <b>(INLG 2018)</b>.'
---
![GitHub Repo stars](https://img.shields.io/github/stars/EagleW/Describing_a_Knowledge_Base?style=social)

[[Paper]](http://aclanthology.org/W18-6502) [[Bib]](https://aclanthology.org/W18-6502.bib) [[Dataset]](https://drive.google.com/open?id=1TzcNdjZ0EsLh_rC1pBC7dU70jINcsVJd) [[Code]](https://github.com/EagleW/Describing_a_Knowledge_Base) [[Slides]](https://eaglew.github.io/files/Wikipedia.pdf)


## Abstract
We aim to automatically generate natural language narratives about an input structured knowledge base (KB). We build our generation framework based on a pointer network which can copy facts from the input KB, and add two attention mechanisms: (i) slot-aware attention to capture the association between a slot type and its corresponding slot value; and (ii) a new table position self-attention to capture the inter-dependencies among related slots. For evaluation, besides standard metrics including BLEU, METEOR, and ROUGE, we also propose a KB reconstruction based metric by extracting a KB from the generation output and comparing it with the input KB. We also create a new data set which includes 106,216 pairs of structured KBs and their corresponding natural language descriptions for two distinct entity types. Experiments show that our approach significantly outperforms state-of-the-art methods. The reconstructed KB achieves 68.8% - 72.6% F-score.

<p align="center">
  <img src="https://eaglew.github.io/images/narratingkb.png?raw=true" alt="Photo" style="width: 100%;"/>
</p>
