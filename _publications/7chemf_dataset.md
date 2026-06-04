---
title: "Chem-FINESE: Validating Fine-Grained Few-shot Entity Extraction through Text Reconstruction"
permalink: /dataset/chemf
date: 2024-01-18
---
![GitHub Repo stars](https://img.shields.io/github/stars/EagleW/Chem-FINESE?style=social)

[[Paper]](https://aclanthology.org/2024.findings-eacl.1.pdf) [[Code]](https://github.com/EagleW/Chem-FINESE) [[Dataset]](https://github.com/EagleW/Chem-FINESE/tree/main/data) [[Slides]](https://eaglew.github.io/files/chemfinese_EACL.pdf) [[Poster]](https://eaglew.github.io/files/EACL2024-poster.pdf) [[Bib]](https://aclanthology.org/2024.findings-eacl.1.bib)


This repositiory contains two chemical few-shot fine-grained entity extraction dataset based on ChemNER and CHEMET.
We choose the values 6, 9, 12, 15, 18 as the potential maximum entity mentions for k-shot for both datasets. 
`annotation` folder contains annotation guidelines and fine-grained entity ontology.
`CHEMET` folder contains full CHEMET dataset and its few-shot subsets. Each folder contains four files: `train.json`, `valid.json`, `test.json`, and `types.json`.
`ChemNER+` folder contains full ChemNER+ dataset and its few-shot subsets. Each folder contains four files: `train.json`, `valid.json`, `test.json`, and `types.json`.
`train.json`, `valid.json`, `test.json` are used for training, validation, and testing respectively. Each file contains multiple lines. Each line represent an instance.
