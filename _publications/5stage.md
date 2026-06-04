---
title: "Stage-wise Fine-tuning for Graph-to-Text Generation"
collection: publications
permalink: /publication/stage
date: 2021-08-03
venue: 'the Joint Conference of the 59th Annual Meeting of the Association for Computational Linguistics and the 11th International Joint Conference on Natural Language Processing 2021 Student Research Workshop (ACL-IJCNLP 2021 SRW)'
citation: '<u><b>Qingyun Wang</b></u>, Semih Yavuz, Xi Victoria Lin, Heng Ji, and Nazneen Fatema Rajani (2021). <b>Stage-wise Fine-tuning for Graph-to-Text Generation</b> <i>in Proceedings of the Joint Conference of the 59th Annual Meeting of the Association for Computational Linguistics and the 11th International Joint Conference on Natural Language Processing 2021 Student Research Workshop</i>. <b>(ACL-IJCNLP 2021 SRW)</b>.'
---

[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/stage-wise-fine-tuning-for-graph-to-text/data-to-text-generation-on-webnlg-full-1)](https://paperswithcode.com/sota/data-to-text-generation-on-webnlg-full-1?p=stage-wise-fine-tuning-for-graph-to-text)
 
![GitHub Repo stars](https://img.shields.io/github/stars/EagleW/Stage-wise-Fine-tuning?style=social)

[[Paper]](https://aclanthology.org/2021.acl-srw.2.pdf) [[Code]](https://github.com/EagleW/Stage-wise-Fine-tuning) [[Dataset]](https://drive.google.com/file/d/18N8xgAftgoV7D03G643EDp1BfQXzPOTH/view?usp=sharing) [[Slides]](https://eaglew.github.io/files/stage_slides.pdf) [[Poster]](https://eaglew.github.io/files/stage-poster.pdf) [[Bib]](https://aclanthology.org/2021.acl-srw.2.bib)


## Abstract
Graph-to-text generation has benefited from pre-trained language models (PLMs) in achieving better performance than structured graph encoders. However, they fail to fully utilize the structure information of the input graph. In this paper, we aim to further improve the performance of the pre-trained language model by proposing a structured graph-to-text model with a two-step fine-tuning mechanism which first fine-tunes model on Wikipedia before adapting to the graph-to-text generation. In addition to using the traditional token and position embeddings to encode the knowledge graph (KG), we propose a novel tree-level embedding method to capture the inter-dependency structures of the input graph. This new approach has significantly improved the performance of all text generation metrics for the English WebNLG 2017 dataset.

<p align="center">
  <img src="https://eaglew.github.io/images/stage.png?raw=true" alt="Photo" style="width: 100%;"/>
</p>

