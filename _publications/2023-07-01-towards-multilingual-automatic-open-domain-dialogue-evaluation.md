---
title: "Towards Multilingual Automatic Open-Domain Dialogue Evaluation"
collection: publications
permalink: /publication/2023-07-01-towards-multilingual-automatic-open-domain-dialogue-evaluation
excerpt: ""
date: 2023-07-01
venue: "SIGDIAL 2023"
paperurl: 'https://aclanthology.org/2023.sigdial-1.11/'
citation: ''
---

The main limiting factor in the development of robust multilingual open-domain dialogue evaluation metrics is the lack of multilingual data and the limited availability of open-sourced multilingual dialogue systems. In this work, we propose a workaround for this lack of data by leveraging a strong multilingual pretrained encoder-based Language Model and augmenting existing English dialogue data using Machine Translation. We empirically show that the naive approach of finetuning a pretrained multilingual encoder model with translated data is insufficient to outperform the strong baseline of finetuning a multilingual model with only source data. Instead, the best approach consists in the careful curation of translated data using MT Quality Estimation metrics, excluding low quality translations that hinder its performance.
