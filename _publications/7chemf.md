---
title: "Chem-FINESE: Validating Fine-Grained Few-shot Entity Extraction through Text Reconstruction"
collection: publications
permalink: /publication/chemf
date: 2024-01-18
venue: 'Findings of the Association for Computational Linguistics: EACL 2024 (EACL 2024 Findings)'
citation: '<u><b>Qingyun Wang</b></u>, Zixuan Zhang, Hongxiang Li, Xuan Liu, Jiawei Han, Huimin Zhao, Heng Ji (2024). <b>Chem-FINESE: Validating Fine-Grained Few-shot Entity Extraction through Text Reconstruction</b> <i>in Proceedings of Findings of the Association for Computational Linguistics: EACL 2024</i>. <b>(EACL 2024 Findings)</b>.'
---
![GitHub Repo stars](https://img.shields.io/github/stars/EagleW/Chem-FINESE?style=social)

[[Paper]](https://aclanthology.org/2024.findings-eacl.1.pdf) [[Code]](https://github.com/EagleW/Chem-FINESE) [[Dataset]](https://github.com/EagleW/Chem-FINESE/tree/main/data) [[Slides]](https://eaglew.github.io/files/chemfinese_EACL.pdf) [[Poster]](https://eaglew.github.io/files/EACL2024-poster.pdf) [[Bib]](https://aclanthology.org/2024.findings-eacl.1.bib)

## Abstract
Fine-grained few-shot entity extraction in the chemical domain faces two unique challenges. First, compared with entity extraction tasks in the general domain, sentences from chemical papers usually contain more entities. Moreover, entity extraction models usually have difficulty extracting entities of long-tailed types. In this paper, we propose Chem-FINESE, a novel sequence-to-sequence (seq2seq) based few-shot entity extraction approach, to address these two challenges. Our Chem-FINESE has two components: a seq2seq entity extractor to extract named entities from the input sentence and a seq2seq self-validation module to reconstruct the original input sentence from extracted entities. Inspired by the fact that a good entity extraction system needs to extract entities faithfully, our new self-validation module leverages entity extraction results to reconstruct the original input sentence. Besides, we design a new contrastive loss to reduce excessive copying during the extraction process. Finally, we release ChemNER+, a new fine-grained chemical entity extraction dataset that is annotated by domain experts with the ChemNER schema. Experiments in few-shot settings with both ChemNER+ and CHEMET datasets show that our newly proposed framework has contributed up to 8.26% and 6.84% absolute F1-score gains respectively.

<p align="center">
  <img src="https://eaglew.github.io/images/chemical_finese.png?raw=true" alt="Photo" style="width: 100%;"/>
</p>

