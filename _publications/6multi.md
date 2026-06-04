---
title: "Multimedia Generative Script Learning for Task Planning"
collection: publications
permalink: /publication/multi
date: 2023-05-04
venue: 'Findings of the Association for Computational Linguistics: ACL 2023 (ACL 2023 Findings)'
citation: '<u><b>Qingyun Wang</b></u>, Manling Li, Hou Pong Chan, Lifu Huang, Julia Hockenmaier, Girish Chowdhary, Heng Ji (2023). <b>Multimedia Generative Script Learning for Task Planning</b> <i>in Proceedings of Findings of the Association for Computational Linguistics: ACL 2023</i>. <b>(ACL 2023 Findings)</b>.'
---
![GitHub Repo stars](https://img.shields.io/github/stars/EagleW/Multimedia-Generative-Script-Learning?style=social)

[[Paper]](https://aclanthology.org/2023.findings-acl.63.pdf) [[Code]](https://github.com/EagleW/Multimedia-Generative-Script-Learning) [[Dataset]](https://drive.google.com/file/d/1lSo-Kr4edNas0_uTl1SvDnEGuPYl0Or9/view?usp=sharing) [[Slides]](https://eaglew.github.io/files/WikiHow_ACL.pdf) [[Poster]](https://eaglew.github.io/files/ACL2023-poster.pdf)  [[Website]](https://virtual2023.aclweb.org/paper_P726.html) [[Bib]](https://aclanthology.org/2023.findings-acl.63.bib)

## Abstract
Goal-oriented generative script learning aims to generate subsequent steps to reach a particular goal, which is an essential task to assist robots or humans in performing stereotypical activities. An important aspect of this process is the ability to capture historical states visually, which provides detailed information that is not covered by text and will guide subsequent steps. Therefore, we propose a new task, Multimedia Generative Script Learning, to generate subsequent steps by tracking historical states in both text and vision modalities, as well as presenting the first benchmark containing 5,652 tasks and 79,089 multimedia steps. This task is challenging in three aspects: the multimedia challenge of capturing the visual states in images, the induction challenge of performing unseen tasks, and the diversity challenge of covering different information in individual steps. We propose to encode visual state changes through a selective multimedia encoder to address the multimedia challenge, transfer knowledge from previously observed tasks using a retrieval-augmented decoder to overcome the induction challenge, and further present distinct information at each step by optimizing a diversity-oriented contrastive learning objective.  We define metrics to evaluate both generation and inductive quality. Experiment results demonstrate that our approach significantly outperforms strong baselines.

<p align="center">
  <img src="https://eaglew.github.io/images/wikihow.png?raw=true" alt="Photo" style="width: 100%;"/>
</p>

