---
title: "PaperRobot: Incremental Draft Generation of Scientific Ideas"
collection: publications
permalink: /publication/paperrobot
date: 2019-7-28
venue: 'The 57th Annual Meeting of the Association for Computational Linguistics (ACL 2019)'
citation: '<u><b>Qingyun Wang</b></u>, Lifu Huang, Zhiying Jiang, Kevin Knight, Heng Ji, Mohit Bansal, and Yi Luan (2019). <b>PaperRobot: Incremental Draft Generation of Scientific Ideas</b> <i>in Proceedings of the 57th Annual Meeting of the Association for Computational Linguistics</i>. <b>(ACL 2019)</b>.'
---
![GitHub Repo stars](https://img.shields.io/github/stars/EagleW/PaperRobot?style=social)

[[Paper]](https://aclanthology.org/P19-1191) [[Bib]](https://aclanthology.org/P19-1191.bib) [[Paper Reading Dataset]](https://drive.google.com/open?id=1DLmxK5x7m8bDPK5ZfAROtGpkWZ_v980Z) [[Paper Writing Dataset]](https://drive.google.com/open?id=1O91gX2maPHdIRUb9DdZmUOI5issRMXMY) [[Code]](https://github.com/EagleW/PaperRobot) [[Poster]](https://eaglew.github.io/files/paperrobot_poster.pdf) [[Sample Output]](https://eaglew.github.io/PaperRobot/)

## Abstract
We present a PaperRobot who performs as an automatic research assistant by (1) conducting deep understanding of a large collection of human-written papers in a target domain and constructing comprehensive background knowledge graphs (KGs); (2) creating new ideas by predicting links from the background KGs, by combining graph attention and contextual text attention; (3) incrementally writing some key elements of a new paper based on memory-attention networks: from the input title along with predicted related entities to generate a paper abstract, from the abstract to generate conclusion and future work, and finally from future work to generate a title for a follow-on paper. Turing Tests, where a biomedical domain expert is asked to compare a system output and a human-authored string, show PaperRobot generated abstracts, conclusion and future work sections, and new titles are chosen over human-written ones up to 30%, 24% and 12% of the time, respectively.

<p align="center">
  <img src="https://eaglew.github.io/images/paperrobot.png?raw=true" alt="Photo" style="width: 100%;"/>
</p>
