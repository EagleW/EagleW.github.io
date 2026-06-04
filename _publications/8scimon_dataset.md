---
title: "SciMON: Scientific Inspiration Machines Optimized for Novelty"
permalink: /dataset/scimon
date: 2024-08-12
--- 
![GitHub Repo stars](https://img.shields.io/github/stars/EagleW/Scientific-Inspiration-Machines-Optimized-for-Novelty?style=social)

[[Paper]](https://aclanthology.org/2024.acl-long.18.pdf) [[Code/Dataset]](https://github.com/EagleW/Scientific-Inspiration-Machines-Optimized-for-Novelty) [[Slides]](https://eaglew.github.io/files/SciMON_ACL.pdf) [[Poster]](https://eaglew.github.io/files/ACL2024-poster.pdf) [[Bib]](https://aclanthology.org/2024.acl-long.18.bib)


This repositiory contains datasets for SciMon Paper. The NLP dataset is based on 67,409 ACL anthology papers from 1952 to 2022. The biomedical dataset is based on 5,704 papers from PubMed.
The project data includes the following components:

1. `data/local_context_dataset.zip`: This folder contains the training, validation, and testing files for our task.
2. `data/kg/*.json`: The `data/kg` directory contains files that store the original Information Extraction (IE) results for all paper abstracts.
3. `data/ct/*.csv`: The `data/ct` directory contains files that represent the citation network for all papers.
4. `data/gold_subset`: This directory contains our gold annotation subsets.
5. `data/biomedical.zip`: This directory contains our biochemical datasets.
6. `evaluation` contain sample evaluation code.
